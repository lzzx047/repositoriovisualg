algoritmo "Questao1"
var
   numeros: vetor[1..10] de inteiro
   i: inteiro
 
inicio
 
   para i de 1 ate 10 faca
      escreva("Digite o ", i, "º número: ")
      leia(numeros[i])
   fimpara
   
   escreval("Números digitados:")
   para i de 1 ate 10 faca
      escreva(numeros[i], " ")
   fimpara
fimalgoritmo
 
