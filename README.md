# MyFome

## Escopo

Com base nas necessidades identificadas no setor de delivery voltado para micro e pequenos empreendedores de fast foods, pizzarias, lanchonetes, sorveterias e restaurantes constatou-se a inexistência de um sistema unificado que facilite a presença online desses estabelecimentos. 
Partindo dessa premissa, nós da Stud.io Tech desenvolvemos e implementamos a ideia de um sistema de catálogo de produtos alimentícios, que permitirá que esses comerciantes possam exibir e gerenciar seus produtos virtualmente, melhorando sua visibilidade e facilitando o acesso dos clientes aos seus serviços.

### Objetivos e Funcionalidades

O MyFome é um aplicativo móvel desenvolvido para atender os clientes, permitindo que eles visualizem as lojas cadastradas, além de explorar os produtos oferecidos por essas lojas. Para os clientes, os pedidos são criados no aplicativo e finalizados diretamente pelo WhatsApp. Já em relação aos empresários, o aplicativo oferece ferramentas completas para gerenciar sua loja, incluindo o cadastro e a administração de produtos.

###  Exclusões do Escopo

O MyFome não é responsável pela gestão de entregas, cobranças ou realização de compras, ficando essas atividades sob a responsabilidade exclusiva de cada empresa.

## Processo

### Clico de Vida

Em princípio, foi adotada ciclos de vida iterativo e incremental para o desenvolvimento deste projeto. Essa escolha permite garantir um crescimento adaptativo ao longo das iterações e incrementos.

### Diagrama do Ciclo de Vida

![diagrama do ciclo de vida do processo](/Artefatos/Iterativo_e_incremental.jpg)

### Tabela de Atividades

| **Fase**          | **(Entrada) Atividade (Saída)**                 | **Papel**                  |
|-------------------|-----------------------------------------------|---------------------------|
| **Concepção**  | ([Contexto](/Processo/Artefatos/Contexto.md)) [**Definir**](/Processo/Atividades/Refinar.md) ([Escopo](/Processo/Artefatos/Escopo.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)           |
| **Concepção**  | ([Escopo](/Processo/Artefatos/Escopo.md)) [**Especificar**](/Processo/Atividades/Criar%20ajustar%20historias%20de%20usuário.md) ([Documento de Requisitos do Produto - PRD](/Processo/Artefatos/Historia%20usuario.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)    
| **Elaboração**  | ([PRD](/Processo/Artefatos/Escopo.md)) [**Escrever**](/Processo/Atividades/Criar%20ajustar%20historias%20de%20usuário.md) ([Histórias de Usuário](/Processo/Artefatos/Historia%20usuario.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)           |
| **Elaboração**  | ([Histórias de Usuário](/Processo/Artefatos/Historia%20usuario.md)) [**Planejar**](/Processo/Atividades/Planejar.md) ([Backlog do Produto](/Processo/Artefatos/Plano%20de%20atendimento.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md)           |
| **Construção** | ([Backlog do Produto](/Processo/Artefatos/Plano%20de%20atendimento.md)) [**Desenvolver**](/Processo/Atividades/Desenvolver.md) ([Produto _Incrementado_](/Processo/Artefatos/Produto%20incrementado.md)) | [Desenvolvedor](/Processo/Papeis/Desenvolvedor.md)  e [Análista de qualidade](/Processo/Papeis/Analista%20de%20qualidade.md)            |
| **Construção** | ([Produto _Incrementado_](/Processo/Artefatos/Produto%20incrementado.md)) [**Testar**](/Processo/Atividades/Revisar%20planejar.md) ([Produto _Ajustado_](/Processo/Artefatos/Produto%20Ajustado.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md) e [Análista de Qualidade](/Processo/Papeis/Analista%20de%20qualidade.md) |
| **Transição** | ([Produto _Ajustado_](/Processo/Artefatos/Produto%20Ajustado.md)) [**Implantar**](/Processo/Atividades/Revisar%20planejar.md) ([Produto Finalizado](/Processo/Artefatos/Produto%20Ajustado.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md) e [Análista de Qualidade](/Processo/Papeis/Analista%20de%20qualidade.md) |
| **Transição** | ([Produto Finalizado](/Processo/Artefatos/Produto%20Ajustado.md)) [**Avaliar**](/Processo/Atividades/Revisar%20planejar.md) ([Documento de Feedback](/Processo/Artefatos/Produto%20Ajustado.md)) | [Dono do Produto](/Processo/Papeis/Dono%20do%20produto.md) e [Análista de Qualidade](/Processo/Papeis/Analista%20de%20qualidade.md) |
---
### Fases do Projeto

#### 1. Planejamento
**Meta:** Garantir que as necessidades do cliente sejam compreendidas, refinadas e priorizadas em pequenos incrementos funcionais (histórias de usuário), organizados em um plano claro de execução.

#### 2.Design
**Meta:** Desenvolver uma experiência visual e interativa que alinhe os objetivos do projeto com as expectativas do usuário, incluindo identidade visual consistente, protótipos navegáveis e guias de estilo claros para garantir a coesão entre design e desenvolvimento.

#### 3. Desenvolvimento
**Meta:** Implementar as funcionalidades planejadas com qualidade, permitindo entregas incrementais e melhorias contínuas por meio de revisões e replanejamento.

## Processo de Gerenciamento

Foi selecionado o Github Project para o processo de gerenciamento de tarefas, no qual foi escolhido o modelo Kanban com colunas padrão:

- **Backlog:** Para tarefas, ideias e mudanças propostas.

- **To Do:** Para tarefas aprovadas e priorizadas.

- **In Progress:** Para tarefas em andamento.

- **Review:** Para mudanças em revisão (ex.: Pull Requests).

- **Done:** Para tarefas concluídas.

Além disso, cada tarefa deverá ter:

- **Título:** curto e descritivo.

- **Descrição:**
  - História de usuário, incluindo:
    - O papel responsável pela a ação. Exemplo: "**Como** desenvolvedor, ...";   
    - A ação desejada. Exemplo: "**Quero** desenvolver a tela de produtos no mobile, ...";
    - E a finalidade. Exemplo: "**Para que** os usuários possam gerenciar e visualizar os produtos.".
          
- **Prioridade (Priority):** Classificação de uma tarefa por nível de urgência e impacto, como:
  - **P0:** Deve ser resolvido imediatamente, pois bloqueia funcionalidades essenciais;
  - **P1:** Necessário resolver em breve, mas não bloqueia o sistema.;
  - **P2:** Pode ser resolvido futuramente, sem impacto crítico.

- **Estimativa (Estimate):** Adição de tempo em horas estimada para a possível finalização da tarefa.

- **Rótulos (Labels):** Classificação do tipo a Issue (ex.: bug, desenvolvimento, design, planejamento).

- **Tipo (Type):** Classificando o tipo da atividade (ex.: bug, feature, task).

- **Tamanho (Size):** Categorização em níveis de complexidade, como:
  - **XS:** Alteração simples (ex: corrigir um erro de digitação);
  - **S:** Pequena refatoração ou adição de um campo no banco;
  - **M:** Implementação de um novo componente ou funcionalidade pequena;
  - **L:** Múltiplas mudanças em diferentes arquivos/módulos;
  - **XL:** Task que envolve pesquisa, integração com API externa ou grande reestruturação.

- **Data de inicio (Start date):** Adicição do tempo de inicialização da tarefa.

- **Data de fim (End date):** Adicição do tempo de finalização da tarefa.

- **Interação (Iteration):** Distribuição de tarefas em sprints. Cada interação deve ter entre 15 (quinze) a 30 (trinta) dias.

- **Responsável (assignees):** Atribuição de um ou mais responsáveis para a execução da tarefa.

[Link do project](https://github.com/orgs/Stud-io-tech/projects/5)


## Controle de Mudanças

O controle de mudanças é um processo estruturado para gerenciar modificações no código-fonte de um projeto, garantindo estabilidade, rastreabilidade e qualidade. Ele define como as alterações são desenvolvidas, testadas e promovidas até a produção, minimizando riscos e falhas. Dessa forma, utilizamos Git como sistema de controle de versão distribuído e GitHub como plataforma para gerenciamento de repositórios, revisão de código e colaboração entre desenvolvedores.

### Fluxo de linhas:

- **Branches das issues/features**:
  - Linhas responsáveis pelo de desenvolvimento;
  - As issues/features são criadas a partir da main, caso seja a primeira a ser criada, ou a partir de outra branche já testada, caso possua outras branches que podem ser aproveitadas.  
  - Cada issue/feature terá sua própria branch para desenvolvimento;
  - Após a implementação, deve-se abrir um Pull Request para a branch "dev";
  - Cada issue/feature deve ser testada antes de ser mergeada para a branch "dev", implementando tanto testes de caixa branca (inspenção, unidade e integração), quanto testes de caixa preta (inteface do usuário).
    
- **Homologação**:
  - Linha responsável por validar as branches criadas antes de ser envida para a produção;
  - Se trata da branch chamada "dev", no qual o código será testado em homologação;
  - Caso todas as branches criadas e testedas sejam validadas com sucesso nesta linha, haverá um Pull Request para a linha de produção;
  - Caso exista algum erro ao realizar a validação de alguma branch enviada para essa linha, serão criadas branches de correção até que tudo esteja validado com sucesso.

- **Produção**:
  - Linha responsável por receber códigos validados pela branche de homologação e por subir o sistema para o servidor de produção automaticamente;
  - Se trata da linha chamada "main";
  - Caso exista algum erro no sistema em produção, será feita a restauração do "commit" anterior, caso exista versões antigas, e serão criadas branches de correção.
    
- **Branches das hotfix/correções de erro:**
  - Linha responsável pela correção de erros verificada na branche de homologação ou produção;
  - Se um erro for identificado nas validações da linha "dev" ou na "main", uma nova branch de hotfix/correção será criada a partir dela;
  - Cada correção será implementada, testada e, se aprovada, integrada novamente à dev, assim como nas branches de issues/features.

### Diagrama de Fluxo:

![Diagrama do Fluxo de Mudanças](/Artefatos/Fluxo%20de%20mudanças.png)

## Prova de conceito (MVP):

Para validar o sistema, foi desenvolvida uma versão inicial que contempla apenas as funcionalidades essenciais do projeto, incluindo:
- Cadastro, Login e logout do lojista;
- Cadastro de lojas e produtos pelos lojistas;
- Listagem de lojas e produtos para os clientes sem precisar estar logado;
- Redirecionamento para finalizar pedidos pelo WhatsApp;

[Link do Aplicativo](https://drive.google.com/drive/folders/1XgvYQ-fs-8wkJKBox98JmKbQZUn_ilcG?usp=drive_link)
