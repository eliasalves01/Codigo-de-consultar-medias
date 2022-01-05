# Codigo-de-consultar-medias
// Código desenvolvido a partir das aulas realizadas pela Dio com total intuito no aprendizado. (PORTUGOL ESTUDIO)

o codigo realizado tem intuito em calcular medias apartir das variaveis alocada ao mesmo. O algoritmo tem base como exemplo o calculo das medias de vendas de um funcionario dentro de uma empresa que segue uma linha de (NOME DA EMPRESA / NOME FUNCIONARIO / VENDAS DO MÊS 1 A MÊS 4)



	
	
	funcao inicio()
	{
	real venda1,venda2,venda3,venda4,media,total 
	cadeia empresa
	cadeia funcionario
	
		escreva("NOME DA EMPRESA FILIAL:")
		leia (empresa)
		escreva("Nome do Funcionario:")
		leia (funcionario)
		escreva("Valores de venda do mês de Janeiro:")
		leia(venda1) // VALOR DO MÊS 1
		escreva("Valores de venda do mês de Fevereiro:")
		leia(venda2) // VALOR DO MÊS 2
		escreva("Valores de venda do mês de Março:")
		leia(venda3) // VALOR DO MÊS 3
		escreva("Valores de venda do mês de abril:")
		leia(venda4)  // VALOR DO MÊS 4

		media = (venda1+venda2+venda3+venda4)/4
		//calcula a média 
		total = (venda1+venda2+venda3+venda4)
		//calcula o valor total

                escreva ("Empresa: " + empresa + "\n" + "Funcionario: " + funcionario + "\n" + "total de vendas R$: " + total + "\n" + "Media mensal R$: " + media )
                   // atua os valores em cadeia 

		se(media>=1000) {
			escreva("\n" + "Parabéns você atingiu sua meta semestral!")
			// verifica se o valor da meta semestral é igual a 1000 ou superior
		}
		
		senao {
			escreva ("\n" + "Você NÃO atigiu sua meta semestral")  	
			// atualiza o status caso a venda seja inferior a 1000
		
		}
	}
}
