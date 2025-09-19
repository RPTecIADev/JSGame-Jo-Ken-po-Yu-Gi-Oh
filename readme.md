
# 🎮 JSGame: Jo-Ken-Po - Edição Duelo de Monstros 🃏
![image](https://github.com/RPTecDev/JSGame-Jo-Ken-po-Yu-Gi-Oh/assets/114440054/02d4fb7c-fc70-4740-9262-a2f8111f50ff)


### "É hora do duelo!" - _Yugi Muto_

Prepare-se, duelista! Você acaba de adentrar em uma arena onde a estratégia ancestral do Jo-Ken-Po (Pedra, Papel e Tesoura) se funde com o poder dos Monstros de Duelo de Yu-Gi-Oh!. Este projeto é uma celebração nostálgica, desenvolvida para demonstrar a manipulação dinâmica do DOM e a lógica de jogo com **JavaScript puro (Vanilla JS)**.

Aqui, cada escolha não é apenas um gesto, mas a invocação de uma carta icônica para o campo de batalha.

## 💻🔗📜 Site do Projeto
[Entre na Arena e Duele Agora!](https://rptecdev.github.io/JSGame-Jo-Ken-po-Yu-Gi-Oh)

Como desenvolvedor sênior, analisei o grimório de códigos deste projeto e fiquei impressionado com a eficiência e a clareza da implementação.

-   **Arquitetura Direta e Eficaz:** O projeto utiliza uma abordagem clássica e robusta com HTML, CSS e JavaScript puros. A estrutura é focada e demonstra um excelente domínio dos fundamentos do desenvolvimento web, sem a necessidade de frameworks complexos.
-   **Manipulação do DOM com Maestria:** O coração do jogo reside no `scripts.js`. A forma como o script captura os eventos do jogador, atualiza a interface (placar, imagens das cartas, resultados) e gerencia o estado do jogo é um exemplo prático e bem executado de manipulação do DOM. Funções como `playHuman` e `playMachine` são claras e coesas.
-   **Lógica de Estado Centralizada:** O uso de um objeto `playerSides` para mapear os campos do jogador e da máquina e um `state` para controlar o placar e as visualizações é uma tática inteligente. Isso centraliza o controle do jogo, tornando o código mais legível e fácil de depurar, uma prática essencial em projetos maiores.
-   **Engajamento Audiovisual:** A adição de áudio (`bgm.mp3` e efeitos sonoros) e a resposta visual imediata (as cartas aparecendo no campo) elevam a experiência de um simples jogo de lógica para um duelo imersivo.

## ✨ Funcionalidades do Disco de Duelo

-   **Duelos Temáticos:** Jogue Pedra, Papel e Tesoura com as cartas de Mago Negro, Dragão Branco de Olhos Azuis e Exodia.
-   **Placar em Tempo Real:** Acompanhe sua pontuação contra a máquina em uma disputa de "melhor de 9" (o primeiro a 5 pontos vence).
-   **Feedback Instantâneo:** Veja as cartas selecionadas e o resultado de cada rodada (Vitória, Derrota ou Empate) no centro da arena.
-   **Trilha Sonora Épica:** Uma música de fundo para manter a adrenalina do duelo (com controle de ligar/desligar).
-   **Design Responsivo:** A arena de duelo se adapta para que você possa jogar em qualquer dispositivo.

## 🛠️ O Deck de Tecnologias

Para construir este campo de duelo, as seguintes cartas foram sacadas do deck:

| Carta Mágica      | Tecnologia   | Descrição da Habilidade                                                                                             |
| :---------------- | :----------- | :------------------------------------------------------------------------------------------------------------------ |
| **O Esqueleto da Arena** | HTML5        | Usado para estruturar todos os elementos do campo de batalha, do placar aos botões de duelo.              |
| **O Feitiço do Estilo** | CSS3         | Responsável por toda a estilização, criando a atmosfera sombria e nostálgica de um verdadeiro duelo.         |
| **A Alma das Cartas** | JavaScript   | O coração do projeto. Controla toda a lógica do jogo, as interações do usuário e as atualizações da interface. |

## 🗺️ Anatomia do Enigma do Milênio (Estrutura do Projeto)

A organização dos artefatos deste projeto foi feita para facilitar a busca por qualquer carta ou feitiço.

```bash
/
├── src/
│   ├── assets/
│   │   ├── audios/      # Efeitos sonoros e trilha sonora do duelo
│   │   ├── icon/        # Ícones e a arte principal do projeto
│   │   └── images/      # Imagens das cartas e do campo de batalha
│   ├── styles/
│   │   ├── animes.css   # Animações e efeitos visuais
│   │   ├── fonts.css    # Fontes temáticas utilizadas
│   │   ├── main.css     # Estilos principais do layout e da arena
│   │   └── reset.css    # Reseta os estilos padrão do navegador
│   └── scripts/
│       └── engine.js    # A mente por trás do duelo: toda a lógica do jogo
└── index.html           # O portal de entrada para a arena
```
## 🚀 Como Iniciar seu Próprio Duelo (Rodando Localmente)

Para ter uma cópia deste projeto e duelar em sua própria máquina, não é necessário nenhum ritual complexo.

1.  **Clone o repositório (Adquira as Cartas Raras):**
    ```bash
    git clone [https://github.com/RPTecIADev/JSGame-Jo-Ken-po-Yu-Gi-Oh.git](https://github.com/RPTecIADev/JSGame-Jo-Ken-po-Yu-Gi-Oh.git)
    ```

2.  **Navegue até a pasta do projeto (Entre na Arena):**
    ```bash
    cd JSGame-Jo-Ken-po-Yu-Gi-Oh
    ```

3.  **Abra o arquivo `index.html` no seu navegador.**

Isso é tudo! Não há dependências ou processos de build. Apenas a pura magia do HTML, CSS e JavaScript.

## 🔮 Visões do Olho do Milênio (Melhorias Futuras)

Todo grande duelista sabe que seu deck sempre pode ser aprimorado.

- [ ] **Seleção de Personagens:** Permitir que o jogador escolha entre Yugi e Kaiba, mudando o tema da arena.
- [ ] **Deck Variado:** Adicionar mais trios de cartas para aumentar a rejogabilidade.
- [ ] **Animações de Batalha:** Criar animações de ataque quando uma carta vence a outra.
- [ ] **Sistema de Pontos de Vida (LP):** Substituir o placar simples por um sistema de 8000 LP, como no anime.





