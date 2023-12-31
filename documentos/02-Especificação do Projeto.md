# Especificação do Projeto

## Perfis de Usuários


<table>
<tbody>
<tr align=center>
<th colspan="2"> Diretoria da Empresa </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Proprietária de um supermercado local</td>
</tr>
<tr></tr>
<td><b>Necessidades</b></td>
<td>Precisa de uma solução fácil de usar para gerenciar o estoque do seu supermercado, reduzindo perdas e maximizando lucros. Ela precisa de relatórios claros sobre vendas e estoque, além de alertas automáticos sobre produtos próximos à validade.</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2"> Gerência </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Gerente de Operações de Supermercado</td>
</tr>
<tr></tr>
<td><b>Necessidades</b></td>
<td>Precisa de uma solução que integre facilmente com os sistemas existentes do supermercado. Ele precisa de recursos avançados, como previsão de demanda, para otimizar as operações diárias.</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2"> Funcionário de supermercado </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Funcionário de Reposição</td>
</tr>
<tr></tr>
<td><b>Necessidades</b></td>
<td>Precisa de uma ferramenta intuitiva para reabastecer as prateleiras com os produtos que não estão na área de venda.</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2"> Auditoria </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Auditora de Perdas</td>
</tr>
<tr></tr>
<td><b>Necessidades</b></td>
<td>Precisa de uma ferramenta que facilite a identificação de padrões de perdas, gere relatórios detalhados e forneça insights sobre áreas de melhoria.</td>
</tr>
</tbody>
</table>

## Histórias de Usuários


|EU COMO... `QUEM`         | QUERO/PRECISO ... `O QUE`                     |PARA ... `PORQUE`                                          |
|--------------------------|-----------------------------------------------|-----------------------------------------------------------|
| Ana Silva (Proprietária) | Receber alertas automáticos quando os produtos estiverem próximos a validade | Evitar perdas financeiras  |                          
| Carlos Oliveira (Gerente de Operações)| Uma integração suave da aplicação de gestão de estoque com os sistemas existentes do supermercado| Garantir uma transição sem problemas|                  
|José Santos (Funcionário de Reposição)|Uma ferramenta para conferir a disponibilidade dos produtos no estoque.| Abastecer os produtos que não estão disponiveis na area de venda|
|Fernanda Oliveira (Auditor de Perdas)| Ser notificada automaticamente sobre picos incomuns de perdas | Investigação imediata e a implementação de medidas corretivas

## Requisitos do Projeto

### Requisitos Funcionais


|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 | O sistema deve permitir o cadastro de novos produtos, incluindo informações como nome, descrição, código de barras, categoria e data de validade, preço unitário e quantidade inicial.| Alta|
| RF-02 | O aplicativo deve oferecer uma visão em tempo real do estoque, destacando produtos com baixo estoque ou próximos à data de validade  | Alta|
| RF-03 | Atualização de estoque. Alertas automáticos devem ser enviados para produtos próximos à validades ou com pouco estoque. O sistema deve permitir a atualização automática do estoque sempre que uma compra for feita ou um produto for vendido. A quantidade disponível deve ser atualizada em tempo real.                                       | Alta|
| RF-04 | Controle de acesso e segurança. O sistema deve ter diferentes níveis de acesso para os usuários (funcionário, gerente e administrador| Alta|                                   
| RF-05 | Geração de relatório. O sistema deve ser capaz de gerar relatórios regulares sobre o status do estoque,incluindo informações sobre produtos em baixa quantidade, produtos mais vendidos e histórico de vendas. Esses relatórios devem ser acessíveis aos gerentes.  | Alta|
| RF-06 | Gerenciamento de Fornecedores. O sistema deve manter um registro de fornecedores, incluindo detalhes de contato e histórico de compras. Isso permite uma gestão eficaz dos relacionamentos e facilita a reposição de estoque.| Alta|
| RF-07 | Integração com o Ponto de Venda (PDV). O sistema de gerenciamento de estoque deve ser integrado ao sistema de ponto de venda para garantir uma sincronização em tempo real entre as vendas e o estoque. Quando um produto é vendido, a quantidade disponível deve ser atualizada automaticamente no estoque.| Alta|

Requisito Funcional: 

**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais


|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 | O aplicativo deve ser responsivo mesmo em grandes volumes de dados | Média | 
| RNF-02 | O tempo de resposta para consultas e atualizações deve ser rápido  | Baixa | 
| RNF-03 |A interface do usuário deve ser intuitiva, facilitando o uso por usuários com diferentes níveis de habilidade técnica | Média | 
| RNF-04 |O aplicativo deve ser compatível com uma variedade de dispositivos e navegadores | Alta | 
| RNF-05 |Implementação de práticas de segurança para proteger dados sensíveis | Alta | 
| RNF-06 |Controle de acesso para diferentes usuários com base em funções | Alta | 
| RNF-07 |Integração suave com outros sistemas do supermercado, como sistemas de vendas e contabilidade |Média|


**Prioridade: Alta / Média / Baixa. 

