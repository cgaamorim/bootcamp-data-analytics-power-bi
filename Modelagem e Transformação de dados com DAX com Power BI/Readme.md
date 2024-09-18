<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Desafio de Projeto: Modelagem e Transformação de dados com DAX com Power BI</span>
</h1>

## Objetivo
Aplicar os conceitos de _Modelagem Dimensional, especificamente o Star Schema_, a um conjunto de dados e-commerce, construindo um modelo de dados a partir de um dataset disponibilizado pelo instrutor.

## Modelagem

Diagrama Star Schema após as técnicas de transformação de dados com Power BI:
![Modelagem Star Schema](der_universidade.png)

	* Fato: As vendas foram definidas como o foco principal da análise, e a tabela `F_Vendas` foi criada para armazenar os dados de fato.
	* Dimensões: Foram criadas diversas tabelas de dimensão para fornecer contexto aos dados de fato: `D_descontos`; `D_detalhes`; `D_Produtos`; `D_Produtos_Detalhes` e `D_calendar`.
  *	Relacionamentos: Os relacionamentos entre as tabelas foram estabelecidos com base na cardinalidade, formando um esquema estrela.
  *	Utilização de DAX: A linguagem DAX foi utilizada para criar a tabela de dimensão temporal e definir hierarquias e granularidades.
