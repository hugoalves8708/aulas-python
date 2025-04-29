# aulas-python

![ilustração linguagem python](https://files.tecnoblog.net/wp-content/uploads/2022/12/python-ari-joury-3-1060x596.jpg)

### Tipos primitivos: string, number(int/float), boolean

Para saber mais, [clique aqui.](https://dev.to/dormin/tipos-primitivos-em-python-10jg)

### Operadores aritméticos
Esses operadores são utilizados para criarmos expressões matemáticas comuns, como soma, subtração, multiplicação e divisão.

Veja quais estão disponíveis no Python:

Operador|Nome|Função
:--------:|:-------:|--------
+|**Adição**|Realiza a soma de ambos operandos.
-|**Subtração**|Realiza a subtração de ambos operandos.
*|**Multiplicação**|Realiza a multiplicação de ambos operandos.
/|**Divisão**|Realiza a Divisão de ambos operandos.
//|**Divisão inteira**|Realiza a divisão entre operandos e a parte decimal de ambos operandos.
%|**Módulo**|Retorna o resto da divisão de ambos operandos.
**|**Exponenciação**|Retorna o resultado da elevação da potência pelo outro.

```py
# Pede para o usuário digitar um número inteiro
numero = int(input("Digite um número inteiro: "))

# Verifica se o número é par ou ímpar
if numero % 2 == 0:
    print(f"O número {numero} é par.")
else:
    print(f"O número {numero} é ímpar.")
```
[Clique aqui](https://pythonacademy.com.br/blog/operadores-aritmeticos-e-logicos-em-python) para saber mais sobre os Operadores Aritméticos.
  
### Operadores lógicos/comparativos
- Estruturas condicionais (if/elif/else)

### Tipos de estruturas condicionais:

- if: Executa um bloco de código se uma condição especificada for verdadeira.
- elif: Significa "else if" e permite que você verifique várias condições.
- else: Executa um bloco de código se nenhuma das condições anteriores for verdadeira.

```py
# Pergunta o nome do usuário
nome = input("Qual é o seu nome? ")

# Verifica se o nome é "Alice" ou "Bob"
if nome == "Alice" or nome == "Bob":
    print(f"Olá, {nome}! Que bom te ver!")
else:
    print(f"Olá, {nome}!")
```
