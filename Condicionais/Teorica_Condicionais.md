## Condicionais

- Forma inicial de comecar a fazer um codigo agir diferente apos avaliar situacoes
- Atraves da analise/suposicao de casos de verdade ou mentira

### Just IF

Sintaxe:

- ```Python

    if CONDICAO:
        #novo escopo(nivel de codigo)
        #So sera executado caso a condicao seja verdadeira
    ```

#### Operadores Logicos

- Conjunto de sinais que realizam comparacoes visando gerar como resultado um Boolean( True ou False)
  - Maior -> >
  - Menor -> <
  - Maior ou igual -> >=
  - Menor ou igual -> <=
  - Igual -> ==
  - Diferente -> !=
  
Problema:

- Suponha que queremos analisar se o aluno é maior de idade apos o input da sua idade. Como faremos isso?

    ```py

    idade = input("Insira a sua idade: ")#Entrada

    # verificando:
    if idade > 18:
        print('Maior de idade')

    if idade <= 18:
        print('Menor de idade')
    ```

Pratique:

- [Bondinho](https://neps.academy/br/course/programacao-basica-(codcad)/lesson/bondinho)