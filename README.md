# Super Trunfo - Nível Novato e Aventureiro

Este é um projeto em C que implementa o jogo **Super Trunfo**, com cartas de cidades.  
O objetivo do projeto é praticar a **leitura de dados do usuário**, o **armazenamento em variáveis**, a **exibição das informações** na tela e cálculos matemáticos simples.

---

## Funcionalidades

### Nível Novato
- Cadastro de **2 cartas** do Super Trunfo.
- Cada carta contém:
  - Estado (A-H)
  - Código da Carta (ex: A01)
  - Nome da Cidade
  - População
  - Área (em km²)
  - PIB (em bilhões de reais)
  - Número de Pontos Turísticos
- Exibição organizada das cartas **após o cadastro**.

### Nível Aventureiro
- Além das funcionalidades do nível novato, o programa calcula e exibe:
  - **Densidade Populacional**: número de habitantes por km².
  - **PIB per Capita**: riqueza média por pessoa na cidade.
- Exibição das novas informações de forma formatada com **duas casas decimais**.

---

## Requisitos

- Sistema operacional: Linux, WSL ou similar.
- Compilador C: `gcc`.

---

## Como Compilar e Rodar

1. Abra o terminal e vá até a pasta onde está o arquivo `super_trunfo.c`:

```bash
cd ~/envs
