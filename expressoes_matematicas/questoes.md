# Soma de números

### Código: m001
### Nível: simples
### Tags: expressões matemáticas, saída

## Enunciado

Escreva um algoritmo para somar dois números e imprimir o resultado na tela.

## Resultados esperados



## Dicas



## Pseudo-código


## Solução (com comentários relevantes)

        INÍCIO
            var n1: inteiro
            var n2: inteiro
            var n3: inteiro
            leia(n1)
            leia(n2)
            n3 = n1 + n2
            mostre('O valor da soma é')
            mostre(n3)
        FIM

----------------------------------------------------------------

# Média entre 3 notas

### Código: m002
### Nível: simples
### Tags: expressões matemáticas, saída

## Enunciado

Escreva um algorimto para calcular a media das 3 notas de um aluno.

## Resultados esperados



## Dicas



## Pseudo-código


## Solução (com comentários relevantes)

        INÍCIO
            var v1: inteiro
            var v2: inteiro
            var v3: inteiro
            var media: inteiro
            leia(v1)
            leia(v2)
            leia(v3)
            media = (v1 + v2 + v3)/3
            mostre('O valor da média é')
            mostre(media)
        FIM

----------------------------------------------------------------

# Área retângulo

### Código: m003
### Nível: simples
### Tags: expressões matemáticas, saída

## Enunciado

Escreva um algoritmo para calcular a área de um retângulo.

## Resultados esperados


## Dicas


## Pseudo-código

## Solução (com comentários relevantes)

        INÍCIO
            var base: inteiro
            var altura: inteiro
            var area: inteiro
            leia(base)
            leia(altura)
            area = base * altura
            mostre('O valor da área é')
            mostre(area)
        FIM

----------------------------------------------------------------

# Cálculo de tijolos em uma parede

### Código: m004
### Nível: simples
### Tags: expressões matemáticas, entrada, saída

## Enunciado

Escreva um algoritmo que solicite ao usuário a largura e a altura de uma parede, e informe a quantidade de tijolos necessários para construir a parede.
Obs.: considerar medidas do tijolo 30 x 10 cm.


## Resultados esperados


## Dicas


## Pseudo-código

## Solução (com comentários relevantes)

        INÍCIO
            var largura: inteiro
            var altura: inteiro
            var area: inteiro
            var tijolos : inteiro
            leia(largura)
            leia(altura)
            area = largura * altura
            tijolos = area/(30*10)
            mostre('O número de tijolos é')
            mostre(tijolos)
        FIM


----------------------------------------------------------------

# Cálculo da idade

### Código: m005
### Nível: simples
### Tags: expressões matemáticas, entrada, saída

## Enunciado

Escreva um algoritmo que calcule a idade de uma pessoa, solicitando mês e ano do seu nascimento.

## Resultados esperados


## Dicas


## Pseudo-código

## Solução (com comentários relevantes)

        INÍCIO
            var mesAtual: inteiro
            var anoAtual: inteiro
            var mesNascimento: inteiro
            var anoNascimento : inteiro
            var idade : inteiro
            leia(mesAtual)
            leia(mesAtual)
            leia(anoNascimento)
            leia(anoNascimento)
            idade = ((mesAtual-mesNacimento) + (anoAtual-anoNascimento)*12)/12
            mostre('Sua idade é')
            mostre(idade)
        FIM

----------------------------------------------------------------

# Fórmula de Baskaras

### Código: m006
### Nível: médio
### Tags: expressões matemáticas, entrada, saída

## Enunciado

Escreva um algoritmo que calcule as raízes de uma equação de 2o. grau, 
sabendo-se os coeficientes a, b e c (equacão de baskaras). Use sqrt para calcular a raíz quadrada.

## Resultados esperados


## Dicas
Use o método Math.sqrt para calcular a raiz quadrada de algum valor.

## Pseudo-código

## Solução (com comentários relevantes)

        INÍCIO
            var a: inteiro
            var b: inteiro
            var c: inteiro
            var delta: inteiro
            var x1: inteiro
            var x2: inteiro
            leia(a)
            leia(b)
            leia(c)
            delta = b*b -4*a*c
            x1 = (-b + sqrt(delta))/2*a
            x2 = (-b - sqrt(delta))/2*a
            mostre('As raízes são:')
            mostre(x1)
            mostre(x2)
        FIM

----------------------------------------------------------------