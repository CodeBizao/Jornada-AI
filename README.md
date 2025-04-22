# 🧠 Dino Runner AI

Este projeto é uma inteligência artificial simples baseada em redes neurais que aprende a jogar o famoso jogo do Dinossauro do Google Chrome (T-Rex Runner) usando mutação genética.

## 🚀 Sobre o Projeto

A ideia principal é criar vários "dinossauros" com redes neurais artificiais (RNA) que aprendem a evitar obstáculos. A cada rodada, a melhor rede é salva e utilizada como base para a próxima geração com pequenas mutações, simulando evolução genética.

## 📁 Estrutura do Projeto

- `index.html`: Página base com informações simples.
- `RNA.js`: Contém a lógica das redes neurais.
- `controls.js`: Simula os comandos de teclado (pular e abaixar).
- `utils.js`: Funções auxiliares, como cálculo de distância.
- `script.js`: Contém a lógica principal de treino e execução do jogo.
- `README.md`: Este arquivo.

## 🧠 Como a IA funciona

1. Cada dinossauro recebe uma rede neural com 3 entradas:
   - Distância até o obstáculo.
   - Velocidade atual.
   - Altura relativa do obstáculo.

2. A rede calcula se deve pular ou abaixar.

3. Após bater no obstáculo, a pontuação é avaliada.

4. A melhor RNA da geração é usada como base para a próxima, com mutações.

## ✅ Requisitos

- Navegador moderno com suporte a módulos JavaScript (ES Modules).
- Acesso ao jogo do dinossauro do Chrome (`chrome://dino`).
- Servidor local como [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) ou outro de sua preferência.

## 🧭 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/dino-runner-ai.git