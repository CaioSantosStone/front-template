## Necessário
-NODE versão 12 >

-Angular CLI versão 9 >

-Recomendado possuir um executador de request exemplo "Postman"

## Execução
-Verificar a imagem de criação de template
-Name test-template

## Descrição Geral e Ajuda

-Deve ser iniciado um projeto do zero em Angular utilizando o AngularCLI.

-A internet e projetos antigos são seus amigos, não queremos e nem esperamos que voce saiba tudo de cabeça, mas que consiga resolver problemas que podem surgir no seu dia a dia, então pode consultar a vontade, somente deixe a tela sendo compartilhada, queremos ver sua evolução.

Então bora para o desafio abaixo:

#### Controle saque de valores disponíveis de transação ####

## Será avaliado
- Simplicidade;
- Consistência da visão das regras de negócio;
- Manutenção;
- Testabilidade.

É necessário que o controle dos saques de valores transacionados em um meio de pagamento sejam gerenciados.
Para iniciar este gerenciamento os seguintes objetivos devem ser alcançados ao realizar a implementação
de sua regra de negócio.

## Objetivos

Realizar o HTML e CSS da imagem proposta.
Realizar o calculo do botão Sacar, existe uma taxa seguindo o seguinte padrão.


-Taxa de debito: 0,4

-Taxa de credito: 1,67

A mesma deve ser aplicada comparando o amount e type da transação.

## JSON Mockado
```
{
transations:[
{
	amount: 40,
	type: 1,
	typeName: 'Crédito',
	statusType: 1,
	statusName: 'Pendente'
},{
	amount: 30,
	type: 1,
	typeName: 'Debito',
	statusType: 1,
	statusName: 'Pendente'
},{
	amount: 30,
	type: 1,
	typeName: 'Debito',
	statusType: 1,
	statusName: 'Pendente'
},{
	amount: 30,
	type: 1,
	typeName: 'Debito',
	statusType: 2,
	statusName: 'Sacado'
}]
}
```
