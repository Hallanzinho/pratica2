# pratica2

algoritmo cotação do dolar


declarações
	dolar1: decimal;
	dolar2: decimal;
	resultado: decimal;

inicio
	ESCREVA("digite a cotação do dolar");
	LEIA(dolar1);
	ESCREVA("digite o valor em dolar  a ser convertido");
	LEIA(dolar2);
	
	resultado<-dolar1*dolar2;

	SE(dolar2<10)então
		ESCREVA("o valor a ser convertido não pode ser menor que 10.");
		
	SENAO
		SE(RESULTADO = 10) ENTAO
			ESCREVA("resultado igual");
		SENAO
			ESCREVA("resultado maior que 10");
		FIM-SE
		
	FIM-SE

	
	
	
	ESCREVA("O resultado é:");
	ESCREVA(resultado);

fim-algoritmo
