# Relatorio-DIO-Projeto-PowerBI
Passo 1: Preparar os Dados
Primeiro, você precisa ter seus dados de vendas prontos. Vamos supor que você tenha um arquivo Excel ou CSV com as seguintes colunas:

Data da Venda
Produto
Quantidade Vendida
Valor da Venda
Região
Vendedor
Categoria do Produto
Passo 2: Importar os Dados no Power BI
Abra o Power BI Desktop.
Clique em Home > Get Data > Excel (ou CSV).
Importe seu arquivo de dados de vendas.
Passo 3: Estrutura Definida do Relatório
Vamos estruturar o relatório em várias páginas:

Visão Geral: KPIs principais, gráficos de barras e linhas.
Vendas por Produto: Detalhamento das vendas por diferentes produtos.
Vendas por Região: Análise de vendas por regiões.
Desempenho por Vendedor: Comparação de desempenho entre vendedores.
Passo 4: Criar Botões de Navegação
Crie uma página adicional chamada Menu que servirá como o ponto de entrada principal.
Vá para a guia Inserir e clique em Botão > Bloco de Texto.
Adicione botões para cada página do relatório (Visão Geral, Vendas por Produto, Vendas por Região, Desempenho por Vendedor).
Formate os botões com texto apropriado e imagens se necessário.
Defina a ação de navegação dos botões: selecione um botão, vá para Formatação do botão > Ação, e defina a navegação para a página desejada.
Passo 5: Segmentadores e Botões com Imagem
Segmentadores: Adicione segmentadores para filtrar dados por data, produto, região, vendedor, etc.
Vá para a página desejada, clique em Inserir > Segmentador.
Selecione o campo para o segmentador, por exemplo, Data da Venda.
Botões com Imagem: Utilize botões com imagens associadas para melhorar a navegabilidade e a usabilidade.
Vá para Inserir > Botão > Imagem.
Adicione imagens que representem diferentes categorias, produtos, ou qualquer outro segmento importante.
Passo 6: Utilizar Indicadores e Botões para Diferentes Visuais
Crie indicadores-chave de performance (KPIs) na página de Visão Geral.
Vá para Visualizações > Cartão e adicione os campos de medida como Receita Total, Volume de Vendas, etc.
Adicione botões interativos para selecionar diferentes visuais sobre o mesmo assunto.
Por exemplo, um botão para alternar entre um gráfico de barras e um gráfico de linhas para as vendas mensais.
Use Bookmarks e Selections para salvar diferentes estados de visualizações e adicionar botões para alternar entre esses estados.
Exemplo de Layout de Página
Página: Visão Geral
Título: Visão Geral das Vendas
KPIs: Receita Total, Volume de Vendas, Margem de Lucro.
Gráfico de Linhas: Vendas Mensais.
Gráfico de Barras: Vendas por Categoria de Produto.
Segmentadores: Data, Região.
Botões de Navegação: Vendas por Produto, Vendas por Região, Desempenho por Vendedor.
Página: Vendas por Produto
Título: Análise de Vendas por Produto
Gráfico de Barras: Vendas por Produto.
Segmentadores: Data, Categoria.
Botões Interativos: Alternar entre Vendas Mensais e Vendas Anuais.
Passo 7: Finalizar e Publicar o Relatório
Revise o relatório para garantir que todos os botões de navegação e segmentadores estão funcionando corretamente.
Salve o projeto.
Publique no Power BI Service para compartilhamento e visualização online.
