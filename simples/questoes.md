# Geração de strings repetidas

### Código: f043
### Nível: simples
### Tags: função string

## Enunciado

Escreva uma função chamada **repetir_string()**, que recebe como parâmetro uma
string **s** e um valor inteiro **n**. Essa função deve retornar uma nova string,
resultado da concatenação da string **s** tantas vezes quanto especificar **n**.

Teste esta função a partir de **main()**.

## Resultados esperados

- **"abc"**  e **3** resulta em **"abcabcabc"**
- **"de"**   e **1** resulta em **"de"**
- **"fghi"** e **0** resulta em **""**

## Dicas

- Utilize uma repetição, **n** vezes.
- Use o operador **+** para concaternar strings.
- A string resultante é criada como um acumulador, que começa com **""**.

## Pseudo-código

        crie uma string vazia chamada resultado
        para cada valor de 1 até n faça
            concatene a string s ao resultado
        retorne o resultado

## Solução (com comentários relevantes)

        public static String repetir_string(String s, int n)
        {
            String resultado = "";
            int i;
            for (i = 1; i <= n; i++) {
                resultado = resultado + s;
            }
            return resultado;
        }

----------------------------------------------------------------

