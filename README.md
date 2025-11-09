# Dashboard de Vendas — Produtos Digitais (Tema: Azul e Cinza)

Este repositório contém um _dashboard_ de vendas criado em Excel, usando uma base de dados simulada com **vendas de produtos digitais** (games, assinaturas e softwares). O objetivo é demonstrar organização de dados, análise visual e geração de insights rápidos.

## Entregáveis
- `dashboard_vendas.xlsx` — planilha Excel com:
  - **Dados**: base simulada (colunas: Data, Produto, Região, Canal de Venda, Quantidade, Valor Unitário, Receita, Custo, Lucro, Mês);
  - **Resumo_Mensal**: tabela resumida por mês (Receita, Lucro, Margem %);
  - **Resumo_Produtos**: resumo por produto (Receita, Quantidade, Lucro);
  - **Resumo_Regiao**: resumo por região (Receita);
  - **Dashboard**: KPIs (Receita total, Lucro total, Margem média), gráfico de vendas mensais, Top 5 produtos e participação por região — com visual limpo em azul/ cinza.

## Como reproduzir / adaptar
1. Abra o arquivo `dashboard_vendas.xlsx` no Excel (versão compatível com gráficos lib).  
2. Na folha **Dados**, substitua a tabela simulada pela sua base real (mantenha os nomes das colunas ou ajuste as fórmulas/links nas abas de resumo conforme necessário).  
3. Atualize os resumos (caso use fórmulas externas) — no Excel, selecione as tabelas e atualize/refresh se necessário.  
4. Para tornar o dashboard interativo com filtros (Slicers), recomendo converter a tabela de **Dados** em uma Tabela do Excel (`Inserir > Tabela`) e então criar Tabelas Dinâmicas e Slicers a partir dela manualmente (isso exige ação dentro do Excel).

## Estrutura de colunas usada na base simulada
- `Data` — data da venda
- `Produto` — nome do produto digital
- `Região` — região geográfica do comprador
- `Canal de Venda` — Website / Mobile App / Partner Store
- `Quantidade` — número de unidades vendidas
- `Valor Unitário` — preço por unidade (R$)
- `Receita` — Quantidade * Valor Unitário
- `Custo` — custo associado (plataforma/fees)
- `Lucro` — Receita - Custo
- `Mês` — coluna auxiliar no formato YYYY-MM

## Observações
- A base é simulada para fins didáticos e contém variações aleatórias para parecer realista.
- Se quiser, eu posso:  
  - adaptar o dashboard à sua base real (se você enviar o `base.xlsx`);  
  - adicionar Tabelas Dinâmicas e Slicers diretamente no arquivo (se preferir mais interatividade).

---
Gerado automaticamente em 2025-11-09 20:09:52
