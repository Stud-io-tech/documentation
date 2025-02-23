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
  - Se um erro for identificado nas validações da linha "dev" ou na "main", uma nova branch de hotfix/correção será criada a partir dela (ex: hotfix/corrige-login);
  - Cada correção será implementada, testada e, se aprovada, integrada novamente à dev, assim como nas branches de issues/features.


### Diagrama de Fluxo:

![Diagrama do Fluxo de Mudanças](/Artefatos/Fluxo%20de%20mudanças.png)
