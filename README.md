# 🐍 AP2-Game: Snake Game Clássico

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-green)
![C Language](https://img.shields.io/badge/C-Language-blue)
![Grade](https://img.shields.io/badge/Grade-10%2F10-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

Este repositório contém o trabalho final da disciplina de **Algoritmos e Programação II**, focado na implementação do clássico jogo da cobrinha (Snake Game) em linguagem C.

## 📄 Sobre o projeto

O objetivo deste projeto é desenvolver uma implementação completa do jogo Snake utilizando programação em C, com manipulação de elementos gráficos, controle de movimento e detecção de colisões.

### 🎯 Objetivos específicos
- Implementar a lógica do jogo Snake com controle de movimento em 4 direções.
- Desenvolver sistema de pontuação baseado na coleta de frutas.
- Criar detecção de colisões com paredes e com o próprio corpo da cobra.
- Implementar menu interativo com opções de jogo, tutorial e níveis de dificuldade.
- Gerenciar velocidade dinâmica da cobra conforme a pontuação aumenta.
- Utilizar manipulação de console para renderização gráfica em tempo real.

## 🎮 Funcionalidades

O jogo oferece as seguintes funcionalidades:

- **Menu principal**: Opções para jogar, acessar tutorial, ajustar níveis de dificuldade e visualizar ranking de pontos.
- **Controles**: Movimentação da cobra usando teclas WASD ou setas direcionais.
- **Sistema de pontuação**: Pontos acumulados ao coletar frutas.
- **Geração aleatória de frutas**: Frutas aparecem em posições aleatórias válidas no tabuleiro.
- **Detecção de colisões**: Game over ao colidir com paredes ou com o próprio corpo.
- **Velocidade progressiva**: A cobra acelera conforme o jogador coleta mais frutas.
- **Opção de replay**: Possibilidade de jogar novamente ou retornar ao menu após o game over.

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido em **C** utilizando as seguintes bibliotecas:

- **stdio.h**: Entrada e saída padrão.
- **stdlib.h**: Funções de utilidade geral.
- **time.h**: Geração de números aleatórios.
- **conio.h**: Controle de entrada do teclado sem buffer.
- **windows.h**: Manipulação de console e cores no Windows.

## 🚀 Como executar

### Pré-requisitos
Certifique-se de ter o compilador GCC instalado no seu sistema Windows.

### Compilação e execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/IagoraNz/AP2-Game
   cd AP2-Game
   ```

2. Compile o código:
   ```bash
   gcc main.c -o snake_game
   ```

3. Execute o jogo:
   ```bash
   ./snake_game
   ```

## 🎯 Como jogar

1. **Controles**:
   - `W` ou `↑`: Mover para cima
   - `A` ou `←`: Mover para esquerda
   - `S` ou `↓`: Mover para baixo
   - `D` ou `→`: Mover para direita

2. **Objetivo**: Colete o máximo de frutas possível sem colidir com as paredes ou com o próprio corpo da cobra.

3. **Pontuação**: Cada fruta coletada aumenta sua pontuação e o tamanho da cobra.

## 📂 Estrutura do repositório

```
📂AP2-Game/
├── 📄 main.c              # Implementação principal do jogo
├── 📄 maincristina.c      # Versão alternativa do código
├── 📂 output/             # Arquivos de saída da compilação
├── 📝 LICENSE             # Licença de uso
└── 📄 README.md           # Documentação do projeto
```

## 📊 Resultados

**Nota Final:** 10/10

O projeto foi avaliado com nota máxima, demonstrando:
- Implementação completa das funcionalidades propostas
- Código bem estruturado e organizado
- Uso adequado de estruturas de dados e funções
- Controle eficiente de fluxo do jogo
- Interface de console funcional e responsiva

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
