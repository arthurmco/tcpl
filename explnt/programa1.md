# Observações sobre os erros do programa exemplo, contidos no primeiro capítulo
[![asciicast](https://asciinema.org/a/p2OwHVZjrptU9tMy45uskMpw7.png)](https://asciinema.org/a/p2OwHVZjrptU9tMy45uskMpw7)

<blockquote>O GCC reclamou pois não houve declaração prévia sobre as funções que foram usadas no código, sendo assim recebemos vários warnings mesmo com a compilação exatamente igual ao exemplo dado, não importando a forma de compilar, os warnings apareceriam pois em todo programa da linguagem C é necessário incluir os cabeçalhos, com os tradicionais</blockquote>
<pre>
```
#include <stdio.h>
#include <stdlib.h>
```
</pre></code>
<blockquote>neste caso seria apenas a <stdio.h>, que contém as funções standard da linguagem para entrada/saída.Além disto o compilador atesta pelo fato de estar apenas Main, antigamente usava-se apenas main, porém agora usamos int main(), dentre esses parênteses contém os argumentos passados no código, porém no exemplo do livro, os (), estão vazios.As chaves {}, envolvem os "comandos" que formam as funções, contudo as "chaves" são mais conhecidas como corpo do código, entre elas estão as principais funções usadas nos códigos, todavia linguagens como Python, não se usa {} e nem ;, em C as coisas são diferentes, se não tivéssemos colocado o ;, o compilador diria que não foi dado um fim para a função. Na linguagem C é imprescindível usar o ;, pois nela é dado como um "fim", assim o computador pode entender melhor que acabou ali e assim prosseguimos nas próximas linhas.</blockquote>
