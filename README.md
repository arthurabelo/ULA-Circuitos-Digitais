# 🚀 Unidade Lógica e Aritmética (ULA)

Este projeto implementa uma Unidade Lógica e Aritmética (ULA) utilizando o Logisim-evolution v3.8.0. A ULA é responsável por realizar operações aritméticas e lógicas em um circuito digital.

## 📋 Pré-requisitos

- Logisim-evolution v3.8.0: [Download](https://github.com/logisim-evolution/logisim-evolution)

## 🛠️ Instruções de Uso

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/arthurabelo/ULA-Circuitos-Digitais.git

2. Abra o arquivo TRABALHO_2_CIRC_DIGI_8_OPERACOES.circ no Logisim-evolution.

3. Execute o circuito para visualizar o funcionamento da ULA.

4. Abra o circuito `MAIN`.

5. Ative o circuito apertando no botão `ON_OFF` e em seguida clique em `LOAD`

6. A cada pulso de `clock` será feita a mudança das entradas e da operação em uma ordem pré-definida.

| Entrada 1 | Entrada 2 | Operação |
|-----------|-----------|----------|
| C         | 0         | 5        |
| A         | 5         | 0        |
| D         | A         | 1        |
| 9         | 9         | 7        |
| 1         | 4         | 7        |
| A         | F         | 0        |
| 8         | 5         | 5        |
| F         | 8         | 4        |

- OBS: Também é permitida entrada manual acessando o circuito `ULA`

## ⚙️ Funcionalidades da ULA
A ULA implementada possui as seguintes operações:

0. Soma (ADD): Realiza a soma de dois operandos.
1. Subtração (SUB): Realiza a subtração de dois operandos.
2. Subtração Complemento de 2: Realiza a subtração de dois operandos por complemento de dois.
3. AND: Realiza a operação lógica AND entre dois operandos.
4. OR: Realiza a operação lógica OR entre dois operandos.
5. NOT A: Realiza a operação lógica NOT no operando A.
6. Complemento de 2 de A: Realiza o complemento de dois da entrada A.
7. Comparador A B: Compara as duas entradas bit a bit.