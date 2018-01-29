# Observações sobre os erros do programa exemplo, contidos no primeiro capítulo
[![asciicast](https://asciinema.org/a/p2OwHVZjrptU9tMy45uskMpw7.png)](https://asciinema.org/a/p2OwHVZjrptU9tMy45uskMpw7)

<blockquote>O GCC reclamou pois não houve declaração prévia sobre as funções que foram usadas no código, sendo assim recebemos vários warnings mesmo com a compilação exatamente igual ao exemplo dado, não importando a forma de compilar, os warnings apareceriam pois em todo programa da linguagem C é necessário incluir os cabeçalhos, com os tradicionais</blockquote>

```C
#include <stdio.h>
#include <stdlib.h>
```


<blockquote>neste caso seria apenas o cabeçalho abaixo que contém as funções standard da linguagem para entrada/saída.Além disto o compilador atesta pelo fato de estar apenas Main, antigamente usava-se apenas main, porém agora usamos int main(), dentre esses parênteses contém os argumentos passados no código, porém no exemplo do livro, os (), estão vazios.As chaves {}, envolvem os "comandos" que formam as funções, contudo as "chaves" são mais conhecidas como corpo do código, entre elas estão as principais funções usadas nos códigos, todavia linguagens como Python, não se usa {} e nem ;, em C as coisas são diferentes, se não tivéssemos colocado o ;, o compilador diria que não foi dado um fim para a função. Na linguagem C é imprescindível usar o ;, pois nela é dado como um "fim", assim o computador pode entender melhor que acabou ali e assim prosseguimos nas próximas linhas.</blockquote>

```C
 #include <stdio.h>
 ```
<blockquote>Em C uma sequência qualquer de número de caracteres entre aspas "...." é chamada de cadeia de caracteres, por ora nosso uso como argumento para printf e outras funções. A notação \n, significa nova linha, ou do inglês  <em>newline</em>






</blockquote>
