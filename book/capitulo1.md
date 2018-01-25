# Capítulo 1-1st chapter

<p>Em C o programa para imprimir "primeiro programa" &eacute;:</p>
<pre>main ()
{
printf("primeiro programa\n");
}
</pre>

# GNU C for compilation
<p>Para compilar: <code>	
gcc -ansi -Wall -pedantic -O3
</code></p>

<blockquote>O modo de executar este programa depende do sistema que você está usando. Como um exemplo específico, no sistema operacional UNIX você deve criar o programa fonte num arquivo cujo nome termine em ".c", tal como primeiro.c e então compilá-lo com o comando 
  <pre>cc primeiro .c</pre> 
  Se você não errar nada, tal como omitir um caractere ou escrever algo errado, a compilação transcorrerá silenciosamente, e produzirá um arquivo executável chamado como a.out
Executando-o com o comando 
<pre>a.out</pre>
produzirá como saída:
<pre>primeiro programa</pre>
  [![asciicast](https://asciinema.org/a/LHUFkpW0aT94zybEPoGL87hOA.png)](https://asciinema.org/a/LHUFkpW0aT94zybEPoGL87hOA)
Em outros sistemas, as regras serão diferentes;verifique com um especialista.
 </blockquote>
 </blockquote>
<h1>Exercício 1-1 | Exercise 1-1</h1>
<p>Execute este programa no seu sistema.Experimente deixar de fora partes do programa pra ver que mensagem de erro você obtém.</p>
