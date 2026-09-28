# semana21modelagem



Relatório – Otimização do Banco de Dados
Nessa atividade, usamos índices para tentar deixar as consultas do banco de dados mais rápidas.

O índice composto foi criado usando id_produto e data_venda. Ele ajuda quando queremos procurar as vendas de um produto em um determinado período. Assim, o banco não precisa procurar em todos os registros.

O índice particionado foi usado na coluna data_venda. Ele separa os dados por períodos, como anos, facilitando a busca de vendas antigas e novas.

Vantagens e limitações
O índice composto ajuda a deixar algumas consultas mais rápidas, principalmente quando usamos as duas colunas. Porém, ele pode ocupar mais espaço no banco.

O índice particionado é útil quando temos muitos dados e queremos organizá-los por data. A desvantagem é que sua configuração pode ser um pouco mais complicada.

Conclusão
Os índices ajudam a melhorar o desempenho do banco de dados. O índice composto é indicado para pesquisas usando mais de uma coluna, enquanto o particionado é interessante para tabelas grandes com muitos dados separados por datas.

Com essas técnicas, a TechTrade pode fazer suas consultas de forma mais rápida e organizada.
