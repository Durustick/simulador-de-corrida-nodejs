# Simulador de Corrida em Node.js

Projeto desenvolvido como desafio do curso de Node.js da DIO. A aplicação simula uma corrida por turnos entre Mario e Luigi, executada no terminal.

## Sobre o projeto

Em cada rodada, o programa sorteia um tipo de trecho da corrida. Os personagens lançam dados e somam o resultado ao atributo relacionado ao trecho. O desempenho determina a pontuação e, nos confrontos, pode haver perda de pontos.

## Funcionalidades

- Simula cinco rodadas automaticamente.
- Sorteia trechos de reta, curva ou confronto.
- Usa os atributos de velocidade, manobrabilidade e poder de cada personagem.
- Aplica pontos, penalidades e bônus de acordo com os resultados aleatórios.
- Exibe no terminal o andamento da corrida e o resultado final.

## Tecnologias e conceitos

- Node.js e JavaScript.
- Objetos para representar personagens e seus atributos.
- Funções assíncronas, condicionais, laços e módulos de aleatoriedade.
- Entrada e saída pelo terminal.

## Requisitos

- Node.js instalado.

## Como executar

Na raiz do projeto, rode:

```bash
node src/index.js
```

Cada execução gera uma corrida diferente, pois os dados e os trechos são sorteados.

## Estrutura

```text
.
├── README.md
└── src/
    └── index.js
```

## Objetivo do desafio

Praticar fundamentos de JavaScript e Node.js criando uma simulação com regras, estado dos jogadores, aleatoriedade e apresentação de resultados.