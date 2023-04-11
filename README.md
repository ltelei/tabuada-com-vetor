# tabuada-com-vetor
tabuada com vetor
Algoritmo "semnome"
//
//
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 10/04/2023
Var
   // Seção de Declarações das variáveis

   tabuada: vetor [1..10,1..3] de inteiro
   resultado,x,num:inteiro



Inicio

   escreval("Digite o numero da tabuada a ser calculada")
   leia(num)
   para x de 1 ate 10 faca
      tabuada[x,1]<-num
      tabuada[x,2]<-x
      tabuada[x,3]<-num*x


   fimpara

   para x de 1 ate 10  faca
      escreval(tabuada[x,1] , " X " , tabuada[x,2]," = ", tabuada[x,3])
   fimpara









Fimalgoritmo
