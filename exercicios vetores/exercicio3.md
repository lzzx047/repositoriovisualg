algoritmo "Questao3"
var
   v: vetor[1..8] de inteiro
   maior, menor, i: inteiro
inicio
   para i de 1 ate 8 faca
      escreva("Digite o ", i, "º valor: ")
      leia(v[i])
      se (i = 1) entao
         maior <- v[i]
         menor <- v[i]
      senao
         se (v[i] > maior) entao maior <- v[i] FimSe
         se (v[i] < menor) entao menor <- v[i] FimSe
      fimSe
   fimPara
   escreval("Maior: ", maior)
   escreval("Menor: ", menor)
fimalgoritmo