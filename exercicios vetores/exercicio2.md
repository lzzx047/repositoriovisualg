 algoritmo "Exercicio2"
   var
      valores: vetor[1..5] de real
      soma: real
      i: inteiro
   inicio
      soma <- 0
      para i de 1 ate 5 faca
         escreva("Digite um valor real: ")
         leia(valores[i])
         soma <- soma + valores[i]
      fimpara
      escreva("A soma total é: " soma)
   fimalgoritmo