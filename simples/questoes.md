# Gera��o de strings repetidas

### C�digo: f043
### N�vel: simples
### Tags: fun��o string

## Enunciado

Escreva uma fun��o chamada **repetir_string()**, que recebe como par�metro uma
string **s** e um valor inteiro **n**. Essa fun��o deve retornar uma nova string,
resultado da concatena��o da string **s** tantas vezes quanto especificar **n**.

Teste esta fun��o a partir de **main()**.

## Resultados esperados

- **"abc"**  e **3** resulta em **"abcabcabc"**
- **"de"**   e **1** resulta em **"de"**
- **"fghi"** e **0** resulta em **""**

## Dicas

- Utilize uma repeti��o, **n** vezes.
- Use o operador **+** para concaternar strings.
- A string resultante � criada como um acumulador, que come�a com **""**.

## Pseudo-c�digo

        crie uma string vazia chamada resultado
        para cada valor de 1 at� n fa�a
            concatene a string s ao resultado
        retorne o resultado

## Solu��o (com coment�rios relevantes)

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

