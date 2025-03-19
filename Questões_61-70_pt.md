61. Qual é a diferença entre uma cópia rasa (shallow copy) e uma cópia profunda (deep copy) em Python?

- [ ] Uma cópia rasa copia apenas o objeto, enquanto uma cópia profunda copia o objeto e todos os objetos aninhados
- [ ] Uma cópia profunda copia apenas o objeto, enquanto uma cópia rasa copia o objeto e todos os objetos aninhados
- [ ] Uma cópia rasa só pode ser usada com listas, enquanto uma cópia profunda funciona com todos os tipos de dados
- [ ] Não há diferença; são dois nomes para a mesma operação

---

62. Escreva uma função Python que usa a função `sorted()` com uma chave personalizada para ordenar uma lista de strings pelo seu comprimento.

---

63. O que o seguinte código irá produzir?
```python
def funcao_externa():
    x = 10
    def funcao_interna():
        nonlocal x
        x = 20
    funcao_interna()
    return x

print(funcao_externa())
```

- [ ] 10
- [ ] 20
- [ ] None
- [ ] Erro

---

64. O que é um gerador em Python? Selecione todas as opções que se aplicam.

- [ ] Uma função que usa a palavra-chave `yield` em vez de `return`
- [ ] Uma estrutura de dados que pode armazenar vários itens
- [ ] Uma maneira de criar iteradores com menor uso de memória
- [ ] Uma classe que cria instâncias de objetos

---

65. Escreva uma função Python que use a função `filter()` para filtrar todos os números pares de uma lista.

---

66. Qual é o propósito de `*args` e `**kwargs` nas definições de funções em Python?

- [ ] `*args` permite que uma função aceite um número variável de argumentos posicionais, e `**kwargs` permite um número variável de argumentos nomeados
- [ ] `*args` e `**kwargs` são usados para fazer funções rodarem mais rápido
- [ ] `*args` desempacota dicionários, e `**kwargs` desempacota listas e tuplas
- [ ] `*args` é para argumentos obrigatórios, e `**kwargs` é para argumentos opcionais

---

67. Crie uma classe simples chamada `Retangulo` com atributos `largura` e `altura`, e métodos para calcular a área e o perímetro.

---

68. Qual é a saída do seguinte código?
```python
numeros = [1, 2, 3, 4, 5]
ao_quadrado = map(lambda x: x**2, numeros)
print(list(ao_quadrado))
```

- [ ] [1, 2, 3, 4, 5]
- [ ] [1, 4, 9, 16, 25]
- [ ] [2, 4, 6, 8, 10]
- [ ] Erro

---

69. Qual das seguintes afirmações sobre o GIL (Global Interpreter Lock) do Python é verdadeira?

- [ ] Ele permite que múltiplas threads executem o bytecode Python ao mesmo tempo
- [ ] Ele impede que múltiplas threads executem o bytecode Python ao mesmo tempo
- [ ] Ele otimiza o gerenciamento de memória em Python
- [ ] Ele está presente apenas no Python 2, não no Python 3

---

70. Escreva uma função Python que use expressões regulares para validar se uma determinada string é um endereço de e-mail válido. 