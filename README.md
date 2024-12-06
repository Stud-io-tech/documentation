# MyFome

## Uma Breve Descrição do Contexto / Problema
Com base nas necessidades identificadas no setor de delivery voltado para micro e pequenos empreendedores de fast foods, pizzarias, lanchonetes, sorveterias e restaurantes localizados em cidades com até 40 mil habitantes, constatou-se a inexistência de um sistema unificado que facilite a presença online desses estabelecimentos. A escolha por cidades menores foi estratégica, considerando o menor custo inicial de tráfego no aplicativo, alinhado ao orçamento disponível para o projeto. Partindo dessa premissa, nós da Stud.io Tech desenvolvemos a ideia de um sistema de catálogo de produtos alimentícios, que permitirá que esses comerciantes possam exibir e gerenciar seus produtos virtualmente, melhorando sua visibilidade e facilitando o acesso dos clientes aos seus serviços.

## O que é o projeto:
O MyFome é um aplicativo móvel desenvolvido para atender os clientes, permitindo que eles visualizem e filtrem as lojas cadastradas em sua cidade, além de explorar os produtos oferecidos por essas lojas. O cliente também pode finalizar suas compras ou pedidos de forma prática, diretamente pelo WhatsApp.

Para os empresários, o aplicativo oferece ferramentas completas para gerenciar suas lojas, incluindo o cadastro e a administração de produtos, bem como o acompanhamento de pedidos e compras relacionados aos itens ofertados.

Por fim, o sistema opera no modelo SaaS (Software como Serviço), no qual os lojistas aderem por meio de uma assinatura mensal sem valor inicialmente estipulado, para acessar e utilizar o serviço.

## O que o projeto não é:
O MyFome não será responsável pela gestão de entregas, cobranças ou realização de compras, ficando essas atividades sob a responsabilidade exclusiva de cada empresa. Além disso, inicialmente, não será disponibilizada a funcionalidade de avaliação por parte dos usuários em relação às lojas e produtos.

## O Porquê do MyFome ser sistema corporativo:

### Automação de Processos: 
O MyFome automatiza tarefas importantes para os empresários, como gerenciamento de produtos e pedidos, oferecendo ferramentas práticas e centralizadas.

### Modelo SaaS: 
Operar como um SaaS indica que o sistema foi projetado para atender a múltiplos clientes (empresários) de maneira escalável e padronizada, características comuns de sistemas corporativos.
### Integração Comercial: 
O aplicativo conecta comerciantes e clientes, fornecendo uma plataforma unificada que melhora a eficiência das operações e facilita a comunicação.

### Gestão Empresarial: 
Oferece funcionalidades que ajudam os empresários a gerenciar seus negócios, o que é típico de soluções voltadas para o setor corporativo.

## Clico de vida e Processo

### Escolha e Justificativa do ciclo de vida
Para o desenvolvimento deste projeto, foi adotada uma abordagem combinando os ciclos de vida iterativo e incremental. Essa escolha permite garantir o crescimento e as alterações previstas ao longo das iterações e incrementos.

### Processo
#### Planejamento Inicial
O planejamento inicial é a base para garantir que o desenvolvimento seja eficiente e organizado.

- **Identificação dos objetivos principais:** Define-se o propósito do sistema, que no caso é fornecer uma plataforma SaaS para lojistas e clientes interagirem, com funcionalidades essenciais como cadastro de lojistas, listagem de produtos e finalização de pedidos via WhatsApp.
  
- **Definição de incrementos:** O projeto é dividido em pequenos incrementos, cada um correspondendo a um conjunto específico de funcionalidades que podem ser entregues de forma independente.
Exemplo:
  - Incremento 1: Cadastro, Login e logout do lojista;
  - Incremento 2: Cadastro de lojas e produtos pelos lojistas;
  - Incremento 3: Listagem de lojas e produtos para os clientes sem precisar estar logado;
  - Incremento 4: Redirecionamento para finalizar pedidos pelo WhatsApp; 
    
- **Criação do backlog:** Lista de tarefas detalhadas para cada incremento.
  
- **Priorização das funcionalidades:** Recursos mais críticos são desenvolvidos primeiro, para garantir que a aplicação tenha valor desde as primeiras entregas.

#### Desenvolvimento Incremental
Cada incremento é tratado como uma entrega funcional do sistema, adicionando progressivamente novos recursos.

- **Entrega de módulos independentes:** Cada incremento inclui o desenvolvimento, teste e entrega de funcionalidades que podem operar de forma independente.
Exemplo: Mesmo que as avaliações dos usuários ainda não sejam implementadas, o sistema de cadastro e exibição de produtos já estará funcionando.

- **Integração contínua:** A cada incremento, as novas funcionalidades são integradas ao sistema existente, garantindo compatibilidade e estabilidade.

- **Teste em pequenos ciclos:** Cada incremento é testado individualmente para assegurar que funcione conforme esperado antes de passar para o próximo.

#### Aperfeiçoamento Iterativo
Esse estágio ocorre paralelamente ao desenvolvimento incremental e é focado em melhorias constantes.

- **Coleta de feedback:** Após cada entrega, obtém-se feedback dos stakeholders (lojistas, clientes e equipe de desenvolvimento). Exemplo: Um lojista pode sugerir melhorias na interface de cadastro de produtos ou no fluxo de finalização de pedidos.

- **Ajustes baseados em aprendizado:** Identificam-se problemas ou pontos de melhoria, e eles são abordados nas iterações seguintes.

- **Refinamento de funcionalidades:** Recursos já entregues podem ser aprimorados com base no feedback e nas métricas de uso.
Exemplo: Melhorar a experiência do cliente ao filtrar produtos ou lojas.

#### Entrega Contínua
Ao final de cada incremento, o sistema é entregue em sua forma funcional, mesmo que esteja incompleto em termos de funcionalidades totais.

- **Versões mínimas viáveis (MVP):** Cada entrega é funcional e agrega valor ao usuário, permitindo que o sistema seja usado mesmo durante o desenvolvimento.
Exemplo: Uma versão inicial pode incluir apenas o cadastro de lojistas e a exibição de lojas para clientes.

- **Validação no ambiente real:** As versões são disponibilizadas para uso real, permitindo identificar problemas ou melhorias necessárias em condições práticas.

- **Redução de riscos:** A entrega contínua reduz o impacto de problemas, pois erros podem ser corrigidos antes de adicionar novos recursos.

#### Adaptação e Escalabilidade
A flexibilidade do modelo iterativo e incremental permite que o projeto acompanhe mudanças nas necessidades dos usuários ou do mercado.

- **Adaptação a novas demandas:** Durante o desenvolvimento, novas funcionalidades podem ser adicionadas ou priorizadas sem comprometer o que já foi entregue.
Exemplo: Adicionar uma funcionalidade para avaliações de usuários com base em demandas do mercado.

- **Escalabilidade do sistema:** A arquitetura é projetada para crescer gradualmente, permitindo suportar mais lojistas, produtos e clientes à medida que o projeto evolui.

- **Monitoramento contínuo:** Métricas de uso e desempenho são monitoradas para ajustar o sistema conforme necessário.

### Rastreabilidade e controle

#### Planejamento inicial:
A criação de documentos e tabelas de versionamento nestes mesmos documentos se fazem presentes.

#### Desenvolvimento Incremental:
O uso de Github Project e Issues fazem parte desse processo.

#### Aperfeiçoamento Iterativo:
O uso de atas de reuniões e documentação, além de conversas informais via WhatsApp se fazem presentes.

#### Entrega Contínua:
O código, testes e documentação que esteja de acordo com os documentos iniciais do incremento se fazem presentes.

# Processo de Desenvolvimento
---
## Tabela de Atividades

| **Fase**          | **(Entrada) Atividade (Saída)**                 | **Papel**                  |
|-------------------|-----------------------------------------------|---------------------------|
| **Planejamento**  | ([Contexto](/Processo/Artefatos/Contexto.md)) [**Refinar**](/Processo/Atividades/Refinar.md) ([Escopo](/Processo/Artefatos/Escopo.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)           |
| **Planejamento**  | ([Escopo](/Processo/Artefatos/Escopo.md)) [**Criar/Ajustar Histórias de Usuário**](/Processo/Atividades/Criar%20ajustar%20historias%20de%20usuário.md) ([Histórias de Usuário](/Processo/Artefatos/Historia%20usuario.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)           |
| **Planejamento**  | ([Histórias de Usuário](/Processo/Artefatos/Historia%20usuario.md)) [**Planejar**](/Processo/Atividades/Planejar.md) ([Plano de Atendimento](/Processo/Artefatos/Plano%20de%20atendimento.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)           |
| **Design** | ([Plano de Atendimento](/Processo/Artefatos/Produto%20incrementado.md)) [**Prototipar**](/Processo/Atividades/Prototipar.md) ([Identidade Visual](/Processo/Artefatos/Identidade%20Visual.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md) e [Designer](/Processo/Papeis/Analista%20de%20qualidade.md) |
| **Desenvolvimento** | ([Plano de Atendimento](/Processo/Artefatos/Plano%20de%20atendimento.md) e [Identidade Visual](/Processo/Artefatos/Identidade%20Visual.md)) [**Desenvolver**](/Processo/Atividades/Desenvolver.md) ([Produto _Incrementado_](/Processo/Artefatos/Produto%20incrementado.md)) | [Desenvolvedor](/Processo/Papeis/Desenvolvedor.md)  e [Análista de qualidade](/Processo/Papeis/Analista%20de%20qualidade.md)            |
| **Desenvolvimento** | ([Produto _Incrementado_](/Processo/Artefatos/Produto%20incrementado.md)) [**Revisar/Replanejar**](/Processo/Atividades/Revisar%20planejar.md) ([Produto _Ajustado_](/Processo/Artefatos/Produto%20incrementado.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md) e [Análista de Qualidade](/Processo/Papeis/Analista%20de%20qualidade.md) |

---

## Metas das Fases

### 1. Planejamento
**Meta:** Garantir que as necessidades do cliente sejam compreendidas, refinadas e priorizadas em pequenos incrementos funcionais (histórias de usuário), organizados em um plano claro de execução.

### 2. Desenvolvimento
**Meta:** Implementar as funcionalidades planejadas com qualidade, permitindo entregas incrementais e melhorias contínuas por meio de revisões e replanejamento.


## Gestão de Mudanças e Evolução do Projeto
Foi selecionado o Github Project para o gerenciamento visual de tarefas. Onde foi escolhido o modelo Kanban com colunas padrão:

- **Backlog:** Para tarefas, ideias e mudanças propostas.

- **To Do:** Para tarefas aprovadas e priorizadas.

- **In Progress:** Para tarefas em andamento.

- **Review:** Para mudanças em revisão (ex.: Pull Requests).

- **Done:** Para tarefas concluídas.

### Gestão de Mudanças com Issues
#### Propostas de Mudanças
Cada solicitação de mudança ou evolução deve ser registrada como uma Issue no repositório. Exemplo de campos na Issue:

- **Título:** Curto e descritivo.

- **Descrição:** Detalhe do problema ou melhoria proposta, incluindo:
  - Justificativa (Por que a mudança é necessária?).
  - Objetivos esperados.
  - Impacto potencial.

- **Rótulos (Labels):** Classifique a Issue (ex.: bug, enhancement, feature, urgent).

- **Milestone:** Relacione a Issue a um marco específico do projeto.

- **Responsável (Assignee):** Atribua a Issue a um responsável.

#### Análise e Priorização
Revisão das Issues em reuniões regulares ou sprints. Avaliando:
- O impacto da mudança nos objetivos do projeto.
- A viabilidade técnica.
- O custo e o esforço necessários.
  
Usando Labels para priorização (high-priority, low-priority, etc.).

## Prova de conceito (MVP):

Para validar o sistema, foi desenvolvida uma versão inicial que contempla apenas as funcionalidades essenciais do projeto, incluindo:
- Cadastro, Login e logout do lojista;
- Cadastro de lojas e produtos pelos lojistas;
- Listagem de lojas e produtos para os clientes sem precisar estar logado;
- Redirecionamento para finalizar pedidos pelo WhatsApp; 
