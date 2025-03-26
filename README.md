# modelagem_de_dados_DER
Exemplo genérico de um diagrama entidade relacionamento baseado no estudo de caso proposto na faculdade.

ESTUDO DE CASO

O ALMA Supermercados possui as seguintes características:

-Cada funcionário do ALMA Supermercados é vinculado a um determinado setor da empresa, podendo ter outros funcionários trabalhando no mesmo setor.

-Cada setor da empresa é cadastrado pelo seu código, sua descrição e sua localização no prédio. 

-O Sistema de Gerenciamento de Banco de Dados (SGBD) deve registrar informações pessoais (nome e data de nascimento) de todos os colaboradores.

-O SGBD precisa cadastrar os projetos, a serem realizados pelos funcionários, por meio de códigos (identificador único), especificando o nome do projeto, o orçamento disponível, a data de início e a data prevista para a conclusão.

-Cada projeto poderá ser realizado individualmente por um funcionário ou por uma equipe de colaboradores. Da mesma forma, um colaborador poderá desenvolver mais de um projeto ao mesmo tempo, ou não.

-Todo colaborador ao ser vinculado a um projeto, deve ser registrado a data da vinculação, a data de desvinculação e a função desempenhada.

-A função de um funcionário não depende do setor que está lotado. 

-Cada função, possui uma remuneração mensal que poderá ser paga de forma integral ou proporcional, caso o colaborador não trabalhe o mês inteiro.

-Cada funcionário pode participar apenas uma vez de cada projeto, ou seja, após a conclusão de um projeto, o funcionário se desvincula e não poderá participar do mesmo projeto, mesmo que mude de função.
