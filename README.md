# Genius Game

Genius Game é uma recriação do clássico jogo de memória onde o jogador deve repetir uma sequência de cores que aumenta de forma progressiva a cada rodada. O objetivo é desafiar sua memória e reflexos, alcançando a maior pontuação possível.

## Funcionalidades

- Interface visual com 4 botões coloridos (verde, vermelho, amarelo e azul).
- Geração automática de sequências aleatórias de cores.
- Feedback visual para cada cor pressionada.
- Incremento de dificuldade a cada nível.
- Contagem de pontos.
- Mensagens de "game over" e reinício automático do jogo.

## Tecnologias Utilizadas

- **HTML**: Estrutura do jogo.
- **CSS**: Estilização e design responsivo.
- **JavaScript**: Lógica do jogo e interatividade.

## Estrutura de Arquivos

```
GeniusGame/
|— src/
    |— style/
    |   |— style.css  # Estilização do jogo
    |— img/
    |   |— genius.jpg  # Ícone do jogo
    |— javascript/
        |— index.js  # Lógica do jogo
|— index.html       # Arquivo principal
```

## Como Jogar

1. **Início do Jogo**:
   - Ao abrir o jogo, uma mensagem de boas-vindas será exibida e a primeira sequência será gerada automaticamente.
2. **Reproduza a Sequência**:
   - Observe as cores que acendem e clique nos botões correspondentes na mesma ordem.
3. **Próximos Níveis**:
   - A cada rodada, uma nova cor é adicionada à sequência. Repita corretamente para continuar jogando.
4. **Game Over**:
   - Caso erre a sequência, o jogo termina e uma mensagem de "game over" é exibida.
5. **Reinício**:
   - Após o "game over", o jogo recomeça automaticamente.

## Controles

- Clique nos botões coloridos para reproduzir a sequência gerada pelo jogo.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/genius-game.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd genius-game
   ```
3. Abra o arquivo `index.html` em qualquer navegador.

## Estilização e Design

O jogo foi projetado com um design responsivo para funcionar em diferentes tamanhos de tela. Utilize os seguintes _media queries_ para ajustes:

- **Telas de até 1080px**: Redução da fonte para 93.75%.
- **Telas de até 720px**: Redução da fonte para 87.5%.

## Personalizações

- **Cores**: Você pode alterar as cores dos botões no arquivo `style.css` ajustando as classes `.blue`, `.red`, `.yellow`, e `.green`.
- **Velocidade**: Para alterar o tempo de iluminação dos botões, modifique o valor em milissegundos na função `lightColor` no arquivo `index.js`.

## Contribuição

1. Fork este repositório.
2. Crie uma _branch_ para sua funcionalidade ou correção:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça _commit_ das suas alterações:
   ```bash
   git commit -m "Adiciona nova funcionalidade"
   ```
4. Envie suas alterações:
   ```bash
   git push origin minha-feature
   ```
5. Abra um _Pull Request_.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

**Divirta-se jogando Genius Game!**
