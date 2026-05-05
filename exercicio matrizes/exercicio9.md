algoritmo "Questao9"
var
   m: matriz[1..4, 1..4] de inteiro
   l, c, maior: inteiro
inicio
   para l de 1 ate 4 faca
      para c de 1 ate 4 faca
         leia(m[l,c])
         se (l = 1) e (c = 1) entao
            maior <- m[l,c]
         senao
            Se (m[l,c] > maior) entao maior <- m[l,c] FimSe
         fimse
      fimpara
   fimpara
   escreva("O maior valor é: ", maior)
fimalgoritmo