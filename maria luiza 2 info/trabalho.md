# 📝 Estruturas de Dados e Identificadores

---

### 1. Identificadores
Os **identificadores** são os nomes atribuídos aos elementos de um programa (como variáveis, funções e classes). Para que sejam válidos, devem respeitar as seguintes regras:

* **Início:** Deve começar obrigatoriamente com uma letra ou sublinhado (`_`).
* **Espaçamento:** Não é permitido o uso de espaços.
* **Restrições:** Não podem ser usados nomes que sejam **palavras reservadas** da linguagem (ex: `if`, `for`, `return`).

#### Exemplo em Python:
```python
# Exemplos de identificadores
nome_usuario = "Alex"  # Válido
_id_interno = 102      # Válido
2nome = "Erro"         # Inválido (começa com número)

# 📘 Variáveis em Java — Guia Completo

## 📌 O que são variáveis?
Variáveis são espaços na memória usados para armazenar valores que podem ser utilizados e modificados durante a execução de um programa.

Em Java, toda variável possui:
- **Tipo** → define o tipo de dado armazenado
- **Nome** → identificador da variável
- **Valor** → dado armazenado

---
Variaveis:
## 🧠 Tipos de Dados em Java
Variáveis são espaços na memória do computador usados para guardar informações que podem ser utilizadas e alteradas durante um programa.

📌 Explicando de forma simples

Pensa em uma variável como uma caixinha com um nome, onde você guarda um valor.

Exemplo:

Nome da variável: idade
Valor guardado: 16

Constante:
### 🔹 Tipos Não Primitivos
Também chamados de **referência**:
- `String`
- Arrays
- Classes

Exemplo:
```java
String nome = "Maria";

# 📘 Constantes em Java — Guia Completo

## 📌 O que são constantes?
Constantes são valores que **não podem ser alterados** durante a execução do programa.

Em Java, usamos a palavra-chave `final` para declarar uma constante.

---

## ⚙️ Declaração de Constantes

### 📌 Sintaxe:
```java
final tipo NOME_DA_CONSTANTE = valor;
📌 Exemplo:
final double PI = 3.14;
final int IDADE_MINIMA = 18;
