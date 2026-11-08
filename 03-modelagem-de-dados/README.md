# 📐 Módulo 03 | Modelagem de Dados
## Desafio Técnico de Modelagem Dimensional

## 📖 Sobre o Desafio Técnico

Desafio técnico desenvolvido durante o **Módulo 03 - Modelagem de Dados** da Formação de Analista de Dados da Educadados.

O objetivo foi estruturar um modelo de dados adequado para análise em Power BI, aplicando conceitos de modelagem dimensional, criação de tabelas fato e dimensão, construção de relacionamentos e organização de atributos analíticos.

A atividade teve como foco a transformação de uma base transacional em um modelo preparado para análises e desenvolvimento de dashboards.


## 🛠️ Tecnologias Utilizadas

-Power BI Desktop
- Power Query
- Modelagem Dimensional



## 📁 Arquivos Disponíveis

| Arquivo | Descrição |
|----------|----------|
| Desafio_Modelagem.pbix | Arquivo Power BI contendo o modelo dimensional desenvolvido |
| Base_Modelagem.xlsx | Base de dados utilizada no desafio |
| modelo-relacionamentos.jpg | Visualização do modelo dimensional e relacionamentos criados |

---

## 📊 Base de Dados

Foi disponibilizada uma base transacional para o desafio, contendo informações de clientes, produtos e vendas.

A partir dessa base, foi realizada a construção de um modelo dimensional seguindo boas práticas de Business Intelligence, incluindo a criação de novas dimensões e a definição dos relacionamentos necessários para análise dos dados.


## 🏗️ Estrutura do Modelo
O modelo foi organizado utilizando o conceito de Star Schema (Modelo Estrela), tendo uma tabela fato central conectada a tabelas dimensão responsáveis pelos atributos analíticos.

### Tabela Fato

#### fVenda

Tabela central responsável pelo registro das transações de vendas, contendo informações relacionadas a:

- Vendas;
- Clientes;
- Produtos;
- Vendedores;
- Canal de venda;
- Datas;
- Valores e quantidades.

## 📚 Dimensões Criadas

| Dimensão | Finalidade |
|-----------|-----------|
| dClientes | Armazena informações cadastrais dos clientes utilizadas em análises de segmentação e comportamento de compra. |
| dProdutos | Contém os atributos dos produtos, permitindo análises por produto, marca e custo. |
| dCanal | Dimensão criada a partir dos canais de venda presentes na tabela fato, permitindo análises por canal de comercialização. |
| dVendedor | Armazena informações dos vendedores e equipes comerciais, separando atributos descritivos da tabela fato. |
| dCalendario | Suporta análises temporais por dia, mês e ano, seguindo boas práticas de modelagem dimensional. |


##  📌 Destaques da Modelagem
    
### dCanal

Dimensão criada a partir da tabela de vendas para normalizar os canais de comercialização e facilitar análises por canal de venda.

### dVendedor

Dimensão criada a partir da tabela fato contendo informações dos vendedores e equipes comerciais.

Após a criação da dimensão:

- Foram mantidos apenas os atributos necessários para identificação do vendedor;
- Os campos descritivos foram removidos da tabela fato para evitar redundância de dados.

### dCalendario

Dimensão temporal criada para suportar análises por período.

Foi realizada a classificação da coluna **Mês Abreviado** pela coluna **Número do Mês**, garantindo a ordenação cronológica correta nas visualizações.

## 🔄 Etapas Realizadas

### Importação dos Dados

- Importação da base disponibilizada para o desafio;
- Identificação das tabelas e atributos necessários para modelagem.

### Classificação das Tabelas

- Identificação da tabela fato;
- Identificação das tabelas dimensão;
- Organização da estrutura analítica.

### Criação das Dimensões

Foram criadas as seguintes tabelas dimensão:

- dCanal;
- dVendedor;
- dCalendario.

### Normalização dos Dados

- Separação dos atributos descritivos da tabela fato;
- Redução de redundâncias;
- Organização do modelo para melhor desempenho analítico.

### Configuração dos Relacionamentos

Foram criados e validados os relacionamentos entre a tabela fato e as tabelas dimensão, garantindo:

- Integridade dos dados;
- Correta propagação dos filtros;
- Consistência das análises.

## 📸 Modelo Dimensional

A imagem abaixo apresenta a estrutura final do modelo criado no Power BI.

./modelo-relacionamentos.jpg


## 🚀 Competências Demonstradas

- Modelagem Dimensional;
- Star Schema (Modelo Estrela);
- Criação de Tabelas Fato e Dimensão;
- Construção de Relacionamentos;
- Normalização de Dados;
- Organização de Modelos Analíticos;
- Criação de Tabela Calendário;
- Boas Práticas em Power BI;
- Preparação de Bases para Dashboards.


## 👩‍💻 Autora

**Silvana Campos**

Desafio técnico desenvolvido durante a Formação de Analista de Dados da Educadados, compondo meu portfólio de projetos em Power BI, Power Query, Modelagem de Dados, DAX e Business Intelligence.

🔗 Repositório Principal:  
https://github.com/SilvanaCampos/portfolio-powerbi-educadados

