
# Projeto de Interface
Nosso projeto de interface oferece uma solução inteligente e eficiente para os desafios enfrentados por estabelecimentos desse setor. Através de uma plataforma intuitiva e de fácil navegação.
## User Flow

Nosso diagrama simplifica a gestão de supermercados. Do login à tela inicial oferecemos adição fácil de produtos e acesso a categorias como gestão de estoque tendo acesso as validades, quantidades e outros detalhes dos produtos de determinadas seções. Os gestores acessam informações cruciais para decisões ágeis e eficazes.


![GES](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146037542/def139d2-ef4c-4665-899c-9463f613d288)


Desenvolver um protótipo emerge como uma das maneiras mais ágeis e econômicas de validar uma ideia, conceito ou funcionalidade. Isso permite a interação, avaliação, modificação e aprovação das principais características de uma interface antes de entrar na fase de desenvolvimento. Leia o artigo [Protótipos: baixa, média ou alta fidelidade?](https://medium.com/ladies-that-ux-br/prot%C3%B3tipos-baixa-m%C3%A9dia-ou-alta-fidelidade-71d897559135).

### Protótipo de baixa fidelidade

Protótipos de baixa fidelidade apresentam de forma simplificada o design da interface e o relacionamento entre suas páginas, permitindo evolução da proposta da solução. Neste projeto, os utilizaremos para apoiar a validação dos requisitos e efetuar mudanças dos mesmos, caso seja necessário, para menor impacto na codificação da aplicação.

### Tela de Login
Formulário inicial em que o usuário informa as credenciais recebidas para acessar a aplicação #Estoque10#. A partir do login o usuário é direcionado a primeira tela do sistema com as opções de módulos disponíveis de acordo com o seu perfil de usuário.

![1](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/6e72adcc-2d9b-4e85-a506-040cac3b7334)

### Interface gráfica da aplicação
Tela inicial da aplicação que permite ao usuário acessar os módulos para visualizar ou executar as ações necessárias para, cadastrar um novo produto, gerenciar estoque, gerenciar fornecedores ou extrar relatório, cadastrar novos usuários e pesquisar operações de usuários dentro do sistema por meio da função de auditoria.
![2](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/050f55cf-d23f-4887-b5ef-e7b2b3c39691)

### Cadastro de novos produtos
Tela em que é disponibilizado ao cliente um formulário de cadastro das informações de um novo produto, com informações de código de barras, categoria do produto, descrição do produto, data de validade, quantidade, preço unitário e lote.
![Schematiq (2)](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/978f7e57-1812-42bf-87ab-f178a4b8f15e)

### Gestão de Estoque
A tela em que é disponibilizado ao cliente uma visão em tempo real do estoque, destacando produtos com baixo estoque ou próximos à data de validade. Alertas automáticos serão enviados para produtos com validade próxima ou com pouco estoque. O sistema permitirá a atualização automática do estoque sempre que uma compra feita ou um produto vendido por uma conexão com o ponto de venda.
![Schematiq (3)](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/66048589-54bd-4bbf-a529-35705eb586d4) 

### Gestão de Fornecedores
A aplicação fornecerá um gerenciamento para manter um registro de fornecedores, incluindo detalhes de contato e histórico de compras. Isso permitirá uma gestão eficaz dos relacionamentos e facilitará a reposição de estoque. A tela abaixo mostra um formulário a ser preenchido pelo usuário para que as informações fiquem disponíveis no módulo de relatório para gerenciamento.
![5](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/4080b41f-3e26-41aa-b9e0-64ac106169f9)

### Módulo de Gestão
O módulo de gestão estará visível apenas para os usuários com perfil administrador ou gerente. Nesse módulo estará disponível o controle de acesso e segurança, auditoria e geração de relatórios. 

### Geração de relatórios
Neste módulo também estará presente a geração de relatório. O sistema será capaz de gerar relatórios regulares sobre o status do estoque, incluindo informações sobre produtos em baixa quantidade, produtos mais vendidos e histórico de vendas. Esses relatórios devem ser acessíveis aos gerentes e administrador. E poderá ser gerados no formato pdf ou excel.
![6](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/3cf632a4-300a-487f-aea6-b6bacc58e61a)

### Cadastro de usuário
Neste formulário, dentro do módulo gestão, será possível cadastrar um novo usuário da aplicação e definir seus níveis de acesso que podem ser: funcionário, gerente ou administrador.
![7](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/db0eb430-e114-4caf-bbc1-be5a27c6df56)

### Função de Auditoria
Neste formulário, dentro do módulo gestão, será possível consultar as operações executadas na aplicação permitindo completa gestão do eventos dentro do sistema.
![8](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e1-proj-web-t14-pmv-ads-2023-2-e1-proj-gestaoestoquesup/assets/146551414/d81db8e4-00d4-43a1-b3fc-6f855d1eeb05)
