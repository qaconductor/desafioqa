# Desafio Conductor de Seleção QA

Olá, queremos convidá-lo a participar de nosso desafio de seleção. Pronto para participar? Seu trabalho será visto por nosso time e você receberá ao final um feedback sobre o que achamos do seu trabalho. Não é legal?
Sobre a oportunidade

A vaga é para Analista de Testes, temos vagas com diversos níveis de senioridade e para cada um deles utilizaremos critérios específicos considerando esse aspecto, combinado? Se você for aprovado nesta etapa, será convidado para uma entrevista final com nosso time de especialistas.

## Desafio Técnico

Nós da Conductor trabalhamos com meios de pagamento e nada melhor uma aplicação confiável, para tanto devemos agilizar nossas entregas e garantir sempre a qualidade das aplicações através de testes automatizados.

- Pré-requisitos:

    * Desenvolver testes automatizados para aplicações Front-end e Back-end(API);

- O que esperamos como escopo mínimo:

    Aplicação Front-end
	
	> * Implementar testes automatizados - login;
    > * Implementar testes automatizados - cadastrar cliente;
	> * Implementar testes automatizados - consultar cliente;
	> * Implementar testes automatizados - realizar venda;
	> * Implementar testes automatizados - consultar venda;

    Aplicação Back-end(API)			
		
	> * Implementar testes automatizados - listar produtos;

- O que será diferencial:

    > * Descrição de possíveis bugs encontrados;
    > * Elaborar plano de testes;
    > * Elaborar relatório(Status reports do seu trabalho).
    
- O que vamos avaliar:

    > * Seu código; 
    > * Organização;
	> * Casos de testes;
	> * Tipos de testes;
    > * Boas práticas;
    > * Diferenciais;    
	
	## Descrição do Desafio
	
	- Aplicação Front-end consiste em um cadastro/Listagem de Clientes e Vendas:
	
		+ Fluxo de Atividade
			+ Menu Cliente
				+ Cadastrar Cliente					
				+ Visualizar Cliente Cadastrado
				+ Listar Cliente
			+ Menu Venda
				+ Cadastrar Venda
				+ Visualizar Venda Cadastrada
				+ Listar Venda			
		
		- Regras de Negócio
		
			1. Autenticação do sistema deve ser realizada com as credenciais(Login/senha: admin/admin);
			2. Campos obrigatórios contêm o símbolo(*);
			3. Para realizar uma Venda apenas deverá ser permitido caso o saldo do cliente for igual ou superior ao valor da compra.		
			
	- Aplicação Back-end consiste em uma listagem de produtos:
	
		+ Fluxo de Atividade
			+ Consumir API de listagem de produtos.	
			
		- Regras de Negócio
			
			1. Header - Token: desafio
