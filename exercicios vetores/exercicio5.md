algoritmo "Questao5"
var
   num: vetor[1..10] de inteiro
   i, contPares: inteiro
inicio
   contPares <- 0
   para i de 1 ate 10 faca
      leia(num[i])
      se (num[i] % 2 = 0) entao
         contPares <- contPares + 1
      fimse
   fimpara
   escreva("Total de números pares: ", contPares)
fimalgoritmo