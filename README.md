inteiro  numero, soma=0
   cadeia continuar = "sim"
    enquanto (continuar == "sim"){
      escreva("Digite um número para somar: ")
      leia(numero)
      soma = soma + numero
      escreva("Deseja continuar 'sim' ou 'não': ")
      leia(continuar)
    }
    escreva("A soma dos números informados é: "+soma )
