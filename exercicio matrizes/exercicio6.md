algoritmo "Questao6"
var
   m: matriz[1..3, 1..3] de inteiro
   l, c: inteiro
inicio
   para l de 1 ate 3 faca
      para c de 1 ate 3 faca
         escreva("Posição [", l, ",", c, "]: ")
         leia(m[l,c])
      fimpara
   fimpara
   para l de 1 ate 3 faca
      para c de 1 ate 3 faca
         escreva(m[l,c]:4)
      fimpara
      escreval("")
   fimpara
fimalgoritmo