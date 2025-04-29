# aulas-python

![ilustração linguagem python](https://files.tecnoblog.net/wp-content/uploads/2022/12/python-ari-joury-3-1060x596.jpg)

### Tipos primitivos: string, number(int/float), boolean

Para saber mais, [clique aqui.](https://dev.to/dormin/tipos-primitivos-em-python-10jg)

### Operadores aritméticos
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
