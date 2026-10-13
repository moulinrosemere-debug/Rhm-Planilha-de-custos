# RHM — Controle de Custos

Aplicação web simples para a RHM Comércio de Produtos Ltda., separada de qualquer projeto da Lopes Tur.

## O que está incluído
- Produtos: código, categoria, unidade, estoque inicial/mínimo, custo, embalagem, etiqueta e preço de venda.
- Compras: fornecedor, quantidade, preço, descontos, frete, outros custos e vencimento.
- Vendas: cliente, pedido, preço, taxas, entrega, recebimentos e saldo.
- Embalagens e etiquetas: quantidade, custo, fornecedor e estoque informado.
- Entregas: transportadora/motoboy, frete cobrado, custo, pedágio e combustível.
- Despesas gerais: impostos, taxas bancárias, comissões e outras despesas.
- Contas a receber: vencimentos, valores recebidos e saldo pendente.
- Painel com faturamento, compras, despesas, lucro estimado, recebíveis e estoque estimado.
- Exportação CSV que pode ser aberta no Excel e backup/restauração em JSON.

## Como abrir online com GitHub Pages
1. Entre em **Settings** neste repositório.
2. Abra **Pages** no menu lateral.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch **main** e a pasta **/(root)**; clique em **Save**.
5. Aguarde a publicação. O endereço normalmente será:
   https://moulinrosemere-debug.github.io/Rhm-Planilha-de-custos/

## Como usar e proteger os dados
- Abra a aplicação e cadastre primeiro os produtos e os custos unitários.
- Registre as compras e vendas usando o mesmo código/SKU para o cálculo do estoque.
- Use **Exportar aba para Excel/CSV** para baixar a aba que estiver aberta.
- Use **Exportar backup** para salvar todos os registros em JSON; **Importar backup** restaura o arquivo.
- Os dados ficam no armazenamento local do navegador e não são compartilhados nem sincronizados entre aparelhos. Limpar os dados do navegador pode apagar os registros. Faça backups regulares.

## Observações
Esta é uma primeira versão local, sem login, banco de dados compartilhado ou sincronização entre usuários. O lucro é uma estimativa gerencial e depende da qualidade dos lançamentos; não substitui a apuração contábil/fiscal. Para cálculo de custos por lote, margem real por pedido, múltiplos usuários e dados sincronizados, será necessário adicionar um banco de dados e autenticação.
