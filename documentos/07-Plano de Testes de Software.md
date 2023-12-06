# Plano de Testes de Software

Pré-requisitos: Especificação do Projeto, Projeto de Interface

Os requisitos para realização dos testes de software são:

Site publicado na internet;
Navegador da internet: Chrome, Firefox ou Edge.
Os testes funcionais a serem realizados na aplicação são descritos a seguir.

| CT-01 - Cadastro de dados |
|:---|:---|CT-01: Verificar o funcionamento do cadastro de informações. |
| Requisitos Associados | RF-01 | O sistema deve permitir o cadastro de novos produtos, incluindo informações como nome, descrição, código de barras, categoria e dados de validade, preço unitário e quantidade inicial. | 
| Objetivo do Teste | Verificar se aplicação permite o cadastro de novos produtos, incluindo informações como nome, descrição, código de barras, categoria e dados de validade, preço unitário e quantidade inicial. |
| Passos | 1. Acessar a página; 2. Digitar informações para cadastro; 3. Salvar; | 
| Critérios de êxito | Visualização correta de todos os itens cadastrados. | 
| Responsável pela elaborar do caso de Teste | Sarah | 

| CT-02 - Controle de validade |
|:---|:---|CT-02: Verificar o funcionamento do cadastro de informações. |
| Requisitos Associados | RF-02 |O aplicativo deve oferecer uma visão em tempo real do estoque, destacando produtos com baixo estoque ou próximos à data de validade | 
| Objetivo do Teste | Verificar se aplicação permite uma visualização facilitada da validade dos produtos cadastrados. |
| Passos | 1. Acessar a home da aplicação; 2. Digitar o nome do produto e categoria pesquisa; 3. Confirmar informações que aparecem para visualiza | 
| Critérios de êxito | Visualização correta da data de validade dos produtos cadastrados. | 
| Responsável pela elaborar do caso de Teste | Sarah | 

| CT-03 - Controle de estoque |
|:---|:---|CT-03: Verificar o funcionamento dos alertas de estoque|
| Requisitos Associados | RF-03 |Atualização de estoque. Alertas automáticos devem ser enviados para produtos próximos à validades ou com pouco estoque. O sistema deve permitir a atualização automática do estoque sempre que uma compra for feita ou um produto for vendido. A quantidade disponível deve ser atualizada em tempo real.| 
| Objetivo do Teste | Verificar se aplicação está sinalizando os alertas que permitam controle de estoque. |
| Passos | 1. Acessar a home da aplicação; 2. simular a retirada de um produto de estoque 4. Consultar os alertas; 3. Confirmar se os alertas aparecem| 
| Critérios de êxito | Visualização de alerta toda vez que um produto é retirado de estoque| 
| Responsável pela elaborar do caso de Teste | Sarah | 

| CT-04 - Controle de segurança |
|:---|:---|CT-04: Verificar o funcionamento controle de acesso |
| Requisitos Associados | RF-04| Controle de acesso e segurança. O sistema deve ter diferentes níveis de acesso para os usuários (funcionário, gerente e administrador.| 
| Objetivo do Teste | Verificar se cada perfil de usuário possui as limitações corretas dentro dos limites precisam operar |
| Passos | 1. Acessar aplicação com cada um dos perfis; 2. Simular operações que excedem as permissões de cada um; | 
| Critérios de êxito | A aplicação impede que o usuário pratique funções além de suas permissões concedidas.| 
| Responsável pela elaborar do caso de Teste | Sarah | 

| CT-05 - Geração de relatório |
|:---|:---|CT-05: Verificar o funcionamento da funcionalidade de emissão de relatórios. | 
| Requisitos Associados | RF-05| O sistema deve ser capaz de gerar relatórios regulares sobre o status do estoque,incluindo informações sobre produtos em baixa quantidade, produtos mais vendidos e histórico de vendas. Esses relatórios devem ser acessíveis aos gerentes.
| Objetivo do Teste | Verificar se a funcionalidade está emitindo os relatórios e se o acesso está restrito ao perfil gerencial |
| Passos | 1. Acessar aplicação com cada um dos perfis; 2. Simular operações que excedem as permissões de cada um; 3. Simular a emissão dos relatórios; | 
| Critérios de êxito | A aplicação permite a emissão de relatórios regulares restritos aos perfis gerencais.| 
| Responsável pela elaborar do caso de Teste | Sarah | 

| CT-06 - Gerenciamento de Fornecedores|
|:---|:---|CT-06: Verificar o correto registro dos fornecedores|
| Requisitos Associados |RF-06| O sistema deve manter um registro de fornecedores, incluindo detalhes de contato e histórico de compras. Isso permite uma gestão eficaz dos relacionamentos e facilita a reposição de estoque.
| Objetivo do Teste | Verificar a assertividade do controle de fornecedores.|
| Passos | 1. Acessar a funcionalidade de gestão de fornecedores; 2. Incluir informações dos fornecedores nos campos da aplicação; 3. Salvar; 4. Consultar as informações inseridas na aplicação; 5. Salvar| 
| Critérios de êxito | A aplicação permite correto registro e controle de fornecedores.| 
| Responsável pela elaborar do caso de Teste | Sarah | 

| CT-07 - Integração com o Ponto de Venda (PDV)|
|:---|:---|CT-07: Verificar conexão com o ponto de venda 
| Requisitos Associados |RF-07 | O sistema de gerenciamento de estoque deve ser integrado ao sistema de ponto de venda para garantir uma sincronização em tempo real entre as vendas e o estoque. Quando um produto é vendido, a quantidade disponível deve ser atualizada automaticamente no estoque.
| Objetivo do Teste | Verificar a assertividade da integração com o ponto de venda.|
| Passos | 1. Simular a retirada no ponto de venda; 2. Observar se aplicação registrou a movimentação.
| Critérios de êxito | A aplicação é capaz de processar as movimentações de saída via PDV.| 
| Responsável pela elaborar do caso de Teste | Sarah | 
