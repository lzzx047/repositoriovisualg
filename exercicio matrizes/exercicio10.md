algoritmo "Questao10"
var
   m: matriz[1..3, 1..4] de real
   l, c: inteiro
   somaLinha: real
inicio
   para l de 1 ate 3 faca
      somaLinha <- 0
      para c de 1 ate 4 faca
         escreva("Linha", l, " Coluna", c, ": ")
         leia(m[l,c])
         somaLinha <- somaLinha + m[l,c]
      fimpara
      escreval("Média da linha ", l, ": ", somaLinha / 4)
   fimpara
fimalgoritmo