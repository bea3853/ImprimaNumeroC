# ImprimaNumeroC
Em Portugol, estudo sobre vetores. o usuário digita os dados na dimensões A e B, a C imprimi ambos. 

algoritmo "ABC"
var
   a: vetor [1..5] de inteiro
   b: vetor [1..10] de inteiro
   i: inteiro
   c:vetor [1..10] de inteiro

inicio
   i:=1
      escreval("A")
   para i de 1 ate 5 faca
           leia(a[i])
    fimpara
    
    escreval(".............")
       escreval("B")
    para i de 1 ate 5  faca

      leia(b[i])

 fimpara
       escreval(".............")
      escreval ("C")
      para i de 1 ate 5 faca
      escreval (a[i], b[i])
      fimpara
fimalgoritmo
