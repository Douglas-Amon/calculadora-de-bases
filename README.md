# calculadora-de-bases
# 🧮 Calculadora de Bases Numéricas

Projeto desenvolvido em Python para a disciplina ECT3401-Computação Numérica que realiza operações entre números em diferentes bases numéricas, incluindo:

* 🔄 Conversão de bases
* ➕ Soma entre números de bases distintas
* ✖️ Multiplicação entre números de bases distintas

---

## 🚀 Funcionalidades

### 1. Conversão de base

Converte um número de uma base qualquer para outra.

📌 Exemplo:

```
Entrada:
1
101,2,10

Saída:
5
```

---

### 2. Soma entre bases diferentes

Realiza a soma de dois números, cada um podendo estar em bases diferentes, e retorna o resultado na base desejada.

📌 Exemplo:

```
Entrada:
3
101,2,A,16,10

Saída:
15
```

---

### 3. Multiplicação entre bases diferentes

Multiplica dois números em bases distintas e retorna o resultado na base escolhida.

📌 Exemplo:

```
Entrada:
2
101,2,3,10,10

Saída:
15
```

---

## 🧠 Como funciona

O programa segue a lógica:

1. Converte os números de entrada para base decimal (base 10)
2. Realiza a operação desejada (soma ou multiplicação)
3. Converte o resultado final para a base solicitada

Também possui suporte para:

* Números com parte fracionária
* Bases maiores que 10 (usando letras A–Z)

---

## 🛠️ Tecnologias utilizadas

* Python 3
* Estruturas de dados básicas (listas, dicionários)
* Manipulação de strings

---

## ▶️ Como executar

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/calculadora-de-bases.git
```

2. Acesse a pasta:

```
cd calculadora-de-bases
```

3. Execute o programa:

```
python calculadora_de_bases.py
```

---

## ⚠️ Formato de entrada

Digite os valores **sem parênteses** e separados por vírgula:

```
numero,base_origem,base_destino
```

ou

```
numero1,base1,numero2,base2,base_destino
```

---

## 📌 Observações

* O programa aceita letras maiúsculas e minúsculas para bases acima de 10.
* A precisão da parte decimal é limitada (até 12 casas).
* Entradas inválidas podem gerar erro, então é importante seguir o formato corretamente.

---

## 👨‍💻 Autor

Douglas Amon - 
Universidade Federal do Rio Grande do Norte (UFRN)

---

## ⭐ Possíveis melhorias

* Interface gráfica (GUI)
* Validação de entrada mais robusta
* Suporte a mais operações (divisão, subtração)
* Melhor tratamento de erros

---
