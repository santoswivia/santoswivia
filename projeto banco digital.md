programa {a
  
  //banco informações
  inteiro bag= 1, bcc=1, bsn=123, i
  caracter voltar
  real saldo=1500, limite=2000, total= limite + saldo, deposito
  
funcao vetor(){

para(i=1; i<=1000; i++){

}

para(i=1; i<1000; i++){

}

Funcao inicio(){

inteiro ag, cc, sn
faca{

escreva("informe o número da agência:\n")
leia(ag)

escreva("informe o número da conta:\n")
leia(cc)

escreva("informe a senha:\n")
leia(sn)
limpa()

}enquanto(bag != ag ou bcc != cc ou bsn != sn)

menu()

  }
   

  funcao menu(){


   inteiro op
   
escreva("escolha uma Operação abaixo\n\n")
escreva(" 1- saldo | 2- extrato | 3- saque | 4- deposito | 5- sair\n\n")
escreva("Opção:\n\n")
leia(op)
limpa()
escolha(op){

caso 1:
saldo()
pare
caso 2:
extrato()
pare
caso 3:
saque()
pare
caso 4:
deposito()
pare
caso 5:
pare

caso contrario: escreva("Opção Invalida, tente novamente")



  }
}

funcao saldo(){

  faca {

escreva("Deseja voltar ao menu s|n?\n")
escreva("saldo:", saldo, "\n")
escreva("limite: ", limite,"\n")
escreva("total:", total, "\n")
leia(voltar)
}

enquanto (voltar != "s")
menu()

}

  funcao extrato(){
  faca {

escreva(saldo + deposito, "\n\n")
escreva("-----------\n\n")

escreva("Deseja voltar ao menu s|n")
leia(voltar)
}

enquanto (voltar != "s")
menu()

}

funcao saque(){

  faca{

escreva("saldo")

  escreva("Deseja voltar ao menu s|n")
  leia(voltar)
 }

 enquanto (voltar != "s")
menu()

 }


funcao deposito(){

  faca{

  escreva("Qual o valor que deseja depositar: ")
  leia(deposito)
  escreva("----------\n\n")


  escreva("Deseja voltar ao menu s|n")
  leia(voltar)
}
enquanto (voltar != "s")
menu()

}
}
--->
