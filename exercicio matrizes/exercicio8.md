algoritmo "Questao8"
var
   m: matriz[1..3, 1..3] de inteiro
   l, c, somaDP: inteiro
inicio
   somaDP <- 0
   para l de 1 ate 3 faca
      para c de 1 ate 3 faca
         leia(m[l,c])
         Se (l = c) entao
            somaDP <- somaDP + m[l,c]
         fimse
      fimpara
   fimpara
   escreva("Soma da diagonal principal: ", somaDP)
fimalgoritmo