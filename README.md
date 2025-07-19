# 🗃️ Modelagem de Banco de Dados - ALMA Supermercados (DER)

Diagrama Entidade-Relacionamento completo para sistema de gestão de funcionários e projetos, desenvolvido como estudo de caso acadêmico.

## 📌 Contexto do Sistema
SGBD para gerenciamento de:
- **Setores** da empresa
- **Funcionários** e suas funções
- **Projetos** alocados

## 🔑 Requisitos Mapeados
| Entidade          | Atributos                          | Relacionamentos                 |
|-------------------|------------------------------------|----------------------------------|
| **Funcionário**   | Nome, Data_Nasc, CPF              | Pertence a 1 Setor              |
| **Setor**         | Código, Descrição, Localização    | Tem N Funcionários              |
| **Projeto**       | Código, Nome, Orçamento, Datas    | Envolve N Funcionários          |
| **Vinculação**    | Data_Início, Data_Fim, Função     | (Tabela associativa)            |

## 🛠️ Tecnologias Utilizadas
- **Lucidchart** (para diagramação DER)
- **Conceitos aplicados**:
  - Cardinalidades (1:N, N:M)
  - Atributos chave
  - Normalização básica

## 📸 Visualização do Diagrama
![Diagrama DER](_Diagrama Entidade-relacionamento do ALMA Supermercados .pdf)

## 💡 Aprendizados Chave
- Identificação de **entidades fracas vs fortes**
- Modelagem de **relacionamentos N:M** com tabela associativa
- Atributos **multivalorados** vs. **atômicos**
- **Dependências funcionais** entre entidades
