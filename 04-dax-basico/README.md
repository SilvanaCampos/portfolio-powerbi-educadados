# 🧮 Módulo 04 | DAX Básico

## Desafio Técnico: Desempenho Comercial da Educadados Academy

## 📖 Sobre o Desafio

Desafio técnico do **Módulo 04 - DAX Básico** da Formação de Analista de Dados da Educadados.

**Cenário:** contratada como Analista de Dados da Educadados Academy, uma escola nacional de cursos de tecnologia, a diretoria queria uma visão clara do desempenho comercial dos últimos dois anos. Foram disponibilizadas três bases: **Clientes**, **Produtos** e **Vendas**.

**Missão:** importar as bases, criar os relacionamentos, criar os cálculos necessários em DAX e entregar apenas os números solicitados, sem necessidade de layout.

## 🛠️ Tecnologias

- Power BI Desktop
- DAX
- Modelagem de Dados
  
# 📁 Arquivos

| Arquivo | Descrição |
|---|---|
| Desafio_DAX_Basico.pbix | Arquivo Power BI com o modelo e as medidas DAX |
| Clientes_Desafio_DAX_Basico.csv | Bases utilizadas no desafio |
| Produtos_Desafio_DAX_Basico.csv | Bases utilizadas no desafio |
| Vendas_Desafio_DAX_Basico.csv | Bases utilizadas no desafio |


## 🔗 Modelo de Dados

O modelo deste módulo é formado pelas três bases do desafio e por uma tabela calendário:

- **Vendas_Desafio_DAX_Basico** (fato): `id_venda`, `data_venda`, `id_cliente`, `id_produto`, `quantidade`, `preco_unitario`, `valor_total`
- **Clientes_Desafio_DAX_Basico**
- **Produtos_Desafio_DAX_Basico**
- **dCalendario**

As medidas ficam organizadas em uma tabela própria, **Medidas**, separadas por pasta de exibição.

