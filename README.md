# Exercicio-15-em-Java
Comando Switch - Livro Cartilha Java


Comando switch
Java oferece o comando switch para controle de fluxo multivalorado, o que é espe-
cialmente útil com tipos enumerados. O exemplo a seguir é indicativo (baseado na 
variável d do tipo Day da Seção 1.1.3).
 switch (d) {
 case MON:
 System.out.println("This is tough.");
 break;
 case TUE:
 System.out.println("This is getting better.");
 break;
 case WED:
 System.out.println("Half way there.");
 break;
 case THU:
 System.out.println("I can see the light.");
 break;
 case FRI:
 System.out.println("Now we are talking.");
 break;
 default:
 System.out.println("Day off!");
 break;
 }
O comando switch avalia uma expressão inteira ou enumeração e faz com que o 
fluxo de controle desvie para o ponto marcado com o valor dessa expressão. Se não 
existir um ponto com tal marca, então o fluxo é desviado para o ponto marcado com 
“default”. Entretanto, este é o único desvio explícito que o comando switch executa, 
e, a seguir, o controle “cai” através das cláusulas case se o código dessas cláusulas 
não for terminado por uma instrução break (que faz o fluxo de controle desviar para 
a próxima linha depois do comando switch).
