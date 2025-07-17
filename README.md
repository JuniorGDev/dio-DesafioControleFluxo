# Desafio Controle de Fluxo 🚀

Este projeto é parte do exercício prático do módulo de **Controle de Fluxo** em Java. O objetivo é criar um programa que simule a contagem de números com base em dois parâmetros fornecidos via terminal, implementando validações e controle de exceções customizadas.

---

## 📋 Descrição

O programa recebe **dois números inteiros como argumentos de linha de comando**:

- Se o **primeiro número for menor que o segundo**, o sistema irá calcular a diferença entre eles e utilizar um laço `for` para imprimir no console o número de interações.
- Caso o **primeiro número seja maior que o segundo**, o sistema deverá lançar uma **exceção customizada** (`ParametrosInvalidosException`) com a seguinte mensagem:
  > O segundo parâmetro deve ser maior que o primeiro

---

## 📁 Estrutura do Projeto

```
DesafioControleFluxo/
├── src/
│   ├── Contador.java
│   └── ParametrosInvalidosException.java
└── README.md
```

---

## 🧠 Exemplo de Execução

### Entrada:

```
java Contador 12 30
```

### Saída:

```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
```

### Caso inválido:

```
java Contador 30 12
```

### Saída:

```
Exception in thread "main" ParametrosInvalidosException: O segundo parâmetro deve ser maior que o primeiro
```

---

## 🧾 Instruções

1. Clone o repositório ou baixe os arquivos.
2. Compile os arquivos com:

```
javac Contador.java ParametrosInvalidosException.java
```

3. Execute com:

```
java Contador <numero1> <numero2>
```

Substitua `<numero1>` e `<numero2>` pelos números desejados.

---

## 💡 Conceitos Utilizados

- Leitura de parâmetros via `args`
- Conversão de Strings para `int`
- Controle de fluxo com `for`
- Lançamento de exceções (`throw`)
- Criação de exceções customizadas (`extends Exception`)

---

## 📌 Observações

- Este exercício foi desenvolvido para reforçar os conceitos de controle de fluxo e tratamento de exceções em Java.
- Certifique-se de estar utilizando o JDK instalado corretamente no seu ambiente.

---

## 🧑‍💻 Autor

Desenvolvido como parte do treinamento de Java.
