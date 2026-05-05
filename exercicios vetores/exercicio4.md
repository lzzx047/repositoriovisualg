algoritmo "Questao4"
var
   vet: vetor[1..6] de inteiro
   i: inteiro
inicio
   para i de 1 ate 6 faca
      leia(vet[i])
   fimPara
   escreval("Ordem inversa:")
   para i de 6 ate 1 passo -1 faca
      escreva(vet[i], " ")
   fimPara
fimalgoritmo