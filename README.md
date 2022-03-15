# exercicio-1
programa
{
	
	funcao inicio()
	{
	     inteiro numeros[5]
		para(inteiro i=0; i < 5; i++){
			escreva(" Informe um valor: ")
			leia(numeros[i])

		}
		limpa()
		para(inteiro j=0; j < 10; j++){
			se(j < 4){
			escreva(numeros[j], ",")
            }
		se(j == 4){
			escreva(numeros[j])
		}
	}

}
