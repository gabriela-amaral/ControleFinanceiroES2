# REQUISITOS

- Funcionais

  * RF01 - O sistema deve possibilitar registrar a(s) despesa(s) do mês corrente;
* O Pagamento a vista, pagamento parcelado e pagamento de contas mensais (luz, telefone) (com data de vencimento)
  * RF02 - O sistema deve possibilitar alterar a(s) despesa(s) do mês corrente;
  * RF03 - O sistema deve possibilitar apagar a(s) despesa(s) do mês corrente;
  * RF04 - o sistema deve possibilitar registrar o pagamento da(s) despesa(s) do mês corrente registrada na RF01;
 
  * RF05 - O sistema deve possibilitar registrar a(s) receita(s) do mês corrente.
  * RF06 - O sistema deve possibilitar alterar a(s) receita(s) do mês corrente;
  * RF07 - O sistema deve possibilitar apagar a(s) receita(s);
  * RF08 - O sistema deve possibilitar registrar o recebimento da(s) receita(s) do mês corrente registrada na RF06;
  
  * RF07 - O sistema deve possibilitar consultar a(s) receita(s);
  * RF08 - O sistema deve possibilitar consultar a(s) despesa(s);
  
  * RF09 - O sistema deve possibilitar criar categoria(s) de receita(s);
  * RF10 - O sistema deve possibilitar alterar a(s) categoria(s) de receita(s);
  * RF11 - O sistema deve possibilitar apagar a(s) categoria(s) de receita(s);
  
  * RF12 - O sistema deve possibilitar criar categoria(s) de despesa(s);
  * RF13 - O sistema deve possibilitar alterar a(s) categoria(s) de despesa(s);
  * RF14 - O sistema deve possibilitar apagar a(s) categoria(s) de despesa(s);
  * RF15 - O sistema deve notificar o usuário após 1 dia de inatividade;
  * RF16 - O sistema deve gerar relatórios textuais;
  * RF17 - O sistema deve gerar relatórios gráficos;
  * RF18 - O sistema deve gerar dicas genéricas de economia;
  
  * RF19 - O sistema de possibilitar registrar (replicar) despesas em longo prazo antecipadamente para os meses seguintes;
  * RF20 - O sistema deve possibilitar pagar as despesas registradas na RF19 por partes;
  
--
- Não Funcionais
	* RNF01 - O sistema deve ser básico;
	* RNF02 - O sistema deve ser fácil sua manutenção;
	* RNF03 - O sistema deve possibilitar segurança para os dados do usuário.
	
	

	
# DETALHAMENTO
- Funcionais

  * RF01 - O sistema deve possibilitar registrar todas as despesas do usuário, no registro tem que preencher o campo de valor, descrição e data de vencimento.
   * RF02 - O sistema deve possibilitar alterar as despesas do mês a correr, para alteração o usuário basta que modifique o campo de valor. 
  * RF03 - O sistema deve possibilitar apagar a despesa do mês corrente, para isso o usuário deve clicar no botão de “Deletar”.
  * RF04 – O sistema de possibilitar registrar o pagamento das despesas do mês corrente registrada na RF01, para realizar o registro basta o usuário clicar no botão “Pagamento Realizado”.
 
  * RF05 - O sistema deve possibilitar que o usuário registre todo o valor recebido até o momento, para o registro o usuário tem que preencher os seguintes campos: valor, descrição.
  * RF06 - O sistema deve possibilitar que o usuário altere as receitas futuras, é necessário que o usuário modifique o seguinte campo: valor.
  * RF07 - O sistema deve possibilitar que o usuário delete alguma receita do sistema, para isso o usuário deve clicar no botão “Deletar Receita”.
  * RF08 - O sistema deve possibilitar registrar o pagamento da(s) despesa(s) do mês corrente registrada na RF06;
  
  * RF07 - O sistema deve possibilitar consultar a(s) receita(s), para isso o usuário deve clicar na aba de consulta e apertar o botão de “Consultar receita”;
  * RF08 - O sistema deve possibilitar consultar a(s) despesa(s), para isso o usuário deve clicar na aba de consulta e apertar o botão de “Consultar despesa”;

  * RF09 - O sistema deve possibilitar criar categoria(s) de receita(s) preenchendo o seguinte campo, tipo de categoria.
  * RF10 - O sistema deve possibilitar alterar a(s) categoria(s) de receita(s), modificando o campo de “Tipo de categoria”;
  * RF11 - O sistema deve possibilitar apagar a(s) categoria(s) de receita(s), para isso o usuário deve clicar no botão de “Deletar Categoria”.
  
  * RF12 - O sistema deve possibilitar criar categoria(s) de despesa(s) com o seguinte dado, tipo de categoria.
  * RF13 - O sistema deve possibilitar alterar a(s) categoria(s) de despesa(s), modificando o campo de “Tipo de categoria”;
  * RF14 - O sistema deve possibilitar apagar a(s) categoria(s) de despesa(s), para isso o usuário deve clicar no botão de “Deletar Categoria”.
  
  * RF15 - O sistema deve notificar o usuário após 1 dia de inatividade; 
  * RF16 - O sistema deve gerar relatórios textuais;
  * RF17 - O sistema deve gerar relatórios gráficos;
  * RF18 - O sistema deve gerar dicas genéricas de economia;
  * RF19 - O sistema de possibilitar registrar (replicar) despesas em longo prazo antecipadamente para os meses seguintes;
  * RF20 - O sistema deve possibilitar pagar as despesas registradas na RF19 por partes;


--
- Não Funcionais


  * RNF01 - O sistema deve ser de fácil utilidade para que possa ser consumido por qualquer tipo de usuário, com botões e campos diretos.
  * RNF02 - O sistema deve ser implementado a objetos, observadas as recomendações GRASP de Craig Larman, e o sistema tem que haver comentário em seus métodos.
  * RNF03 - O sistema deve possibilitar segurança para os dados do usuário.

---
