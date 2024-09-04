PROJETO INTEGRADOR - WEB 2024.1

1. Descrição/Briefing
O cliente fabrica máquinas industriais e necessita de um sistema que controle tanto
a compra das peças necessárias para a fabricação das máquinas quanto a venda
das mesmas.
2. Levantamento de Requisitos
2.1 Necessidades/Requisitos funcionais
● Calcular frete: diluir o valor do frete como custo unitário dos produtos
● Atualizar valor em dólar da máquina: buscar o valor em dólar de uma API e
atualizar o campo
● Limitar venda dupla: não deixar o usuário cadastrar duas vendas iguais no
prazo de 5 minutos
● Baixa no estoque: todas as compras e vendas geram alteração na
quantidade de peças em estoque
● Cadastro de vendas
○ código da venda
○ número da nota fiscal
○ nome do vendedor
○ comissão do vendedor (em percentual)
○ valor de venda da máquina
○ número de série da máquina
○ data e hora da venda
○ data de expiração da garantia (1 ano após a data da venda)
● Cadastro de cliente
○ código do cliente
○ nome
○ CPF ou CNPJ
○ endereço com CEP
○ telefone
○ observação
● Cadastro de peças
○ código da peça
○ nome peça
○ preço em real
○ endereço/localização no almoxarifado
○ quantidade em estoque

● Cadastro de máquinas
○ nome da máquina
○ lista de peças
■ peça
■ quantidade
■ valor total
○ valor de custo da máquina em reais
○ valor de custo da máquina em dólares
● Relatório de compras
○ nome da máquina
○ quantidade de máquinas
○ lista de peças
■ peça
■ quantidade x quantidade de máquinas
■ valor total das máquinas em reais
■ valor total das máquinas em dólar

● Relatório de vendas
○ mês
○ quantidade de máquinas vendidas
○ valor produzido (custo)
○ valor faturado (receita)
○ lucro

2.2 Exigências/Requisitos não funcionais
- Sistema web
- Duas permissões de usuário: Administrador e Funcionário
- Tecnologias recentes
2.3 Desejos/Projetos de melhoria
- Integração com Nota Fiscal Eletrônica
- Notificações de compras quando o estoque estiver baixo

3. Time de Desenvolvimento
Cadastro de Vendas - Garcês, Diarã, Bruno
Cadastro de Cliente -, Julimar, Thiago, Krystian
Cadastro de Peças - João Victor, Marco Antônio, Hana
Cadastro de Máquinas - Gustavo, Julio, Marcos Vinícius
Relatório de Compras - Garcês, Thiago, Gustavo, Julio, João Victor, Krystian
Relatório de Vendas - Diarã, Hana, Marcos Vinícius, Julimar, Marco Antônio, Bruno
