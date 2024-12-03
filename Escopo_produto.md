
# Escopo do Produto MyFome - Primeiro MVP

## Projeto: MyFome

## Registro de Alterações:

| **Versão** | **Responsável**               | **Data**   | **Alterações**                                           |
| ---------- | ----------------------------- | ---------- | -------------------------------------------------------- |
| 0\.1       | Lázaro Luis Martins Alexandre | 02/12/2024 | Versão inicial, contendo as seções 1, 2, 3, 4, 5, 6 e 7. |
##
## 1. Descrição
Considerando os desafios enfrentados por restaurantes e estabelecimentos de pequeno e médio porte na organização de cardápios, no gerenciamento de pedidos e na comunicação eficaz com clientes, surgiu a necessidade de criar o sistema “MyFome”. Essa solução, disponível em plataforma móvel, visa otimizar o processo de exibição de cardápios, integrar o fluxo de pedidos e facilitar o contato direto com os clientes através do WhatsApp, promovendo eficiência operacional.
## 2. Requisitos
Tomando por base o contexto do sistema, foram identificados os seguintes requisitos:

**Requisitos funcionais**

| ID   | Caso de Uso       | Descrição                                                                                                                                                                                                                                         | Prioridade | Dependência |
| :--- | :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :--------- | :---------- |
| RF01 | Registrar Conta   | <p>O sistema deve permitir que os usuários realizem registro.</p><p>**Dados de registro:** nome, email e imagem.</p><p>**Dados gerais de usuário:** id\_usuario, nome, email, imagem, ativo, data\_criado e data\_atualizado.</p>                 | Alta       |             |
| RF02 | Fazer Login       | <p>O sistema deve permitir que os usuários realizem autenticação.</p><p>**Dados de autenticação:** email.</p>                                                                                                                                     | Alta       | RF01        |
| RF03 | Gerenciar Loja    | <p>O sistema deve permitir que o usuário gerencie sua loja virtual.</p><p>**Dados de loja:** id\_loja, nome, descricao, imagem, whatsapp, ativo, data\_criado e data\_atualizado.</p>                                                             | Alta       | RF02        |
| RF04 | Gerenciar Produto | <p>O sistema deve permitir que os usuários gerenciem produtos da sua própria loja virtual.</p><p>**Dados de produto:** id\_produto, nome,  descricao, imagem, preco, quantidade, id\_loja, vendidos, ativo,  data\_criado e data\_atualizado.</p> | Alta       | RF03        |
| RF05 | Fazer Pedido      | <p>O sistema deve permitir que os usuários façam pedidos. </p><p>**Dados de Pedido:** id\_produto, quantidade</p>                                                                                                                                 | Alta       |             |

**Regras de negócio**

| ID   | Descrição                                                                                                                                                       |
| :--- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RN01 | Os usuários não autenticados poderão navegar no aplicativo, a fim de visualizar lojas e produtos, além de realizar pedidos.                                     |
| RN02 | Os usuários devem se autenticar e se registrar exclusivamente via conta google.                                                                                 |
| RN03 | Nada será apagado permanentemente no banco de dados, apenas suspensos temporariamente.                                                                          |
| RN04 | O MyFome não se responsabilizará por qualquer tipo de desacordo entre o cliente e o vendedor em relação ao pagamento e a entrega do produto fora do aplicativo. |

**Requisitos não funcionais**

| ID    | Descrição                                                                                                                                                                             | Categoria                               | Prioridade |
| :---- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------------------------------------- | :--------- |
| RNF01 | O aplicativo móvel deve ser responsivo, ou seja, deve ser adequado para uso em diferentes dispositivos móveis, como tablets e smartphones.                                            | Usabilidade / Responsividade            | Alta       |
| RNF02 | O sistema deve ser seguro, protegendo as informações dos usuários e evitando acesso não autorizado aos dados.                                                                         | Segurança / Confidencialidade           | Alta       |
| RNF03 | O sistema deve ter uma interface intuitiva e de fácil utilização, proporcionando uma experiência amigável para os usuários, independentemente do seu nível de habilidade tecnológica. | Usabilidade / Facilidade de aprendizado | Alta       |
| RNF04 | O sistema deve garantir a privacidade e conformidade com as leis de proteção de dados, como a Lei Geral de Proteção de Dados (LGPD) no Brasil ou outras regulamentações aplicáveis.   | Confiabilidade / Privacidade            | Alta       |
| RNF05 | O backend do sistema deve ser feito utilizando o framework Laravel                                                                                                                    | Manutenibilidade/ Modularidade          | Alta       |
| RNF06 | O frontend  do sistema deve ser feito utilizando framework Flutter                                                                                                                    | Manutenibilidade / Modularidade         | Alta       |
| RNF07 | O SGBD utilizado será o PostgresSQL                                                                                                                                                   | Manutenibilidade / Modularidade         | Média      |

## 4. Diagrama de Caso de Uso
![Diagrama de Caso de Uso](./Diagrama%20de%20caso%20de%20uso.png)

## 5. Modelo Lógico de Banco de Dados
![Modelo Lógico de Banco de Dados](./Modelo%20Lógico%20de%20Banco%20de%20Dados.png)

## 6. Diagrama de Class
![Diagrama de Class](./Diagrama%20de%20Classe.png)

## 7. Diagrama de Componentes
![Diagrama de Componentes](./Diagrama%20de%20Componentes.png)