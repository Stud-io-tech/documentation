# Em um sistema corporativo, onde os componentes geralmente precisam ser flexíveis e fáceis de manter, como vocês acham que a escolha entre herança e composição pode impactar a maneira como os componentes interagem? E como isso afeta a facilidade e a confiabilidade dos testes de cada parte do sistema?

O sistema deve ser mais flexivel e fácil de manter onde há os seus requisitos principais, ou seja, onde o sistema realmente resolve o problema se tratando assim da prova de conceito ou MVP.

A escolha entre Composição e Herança impacta no desenvolvimento e manutenção dos componentes, se usarmos herança que não possuem uma especialização em um cenário que há muitas refatorações e atualizações as chances de erros e ocorrerem e mais código se reimplementado aumentam. Por outro lado, se usarmos composição em um cenário de classe muito parecidas, teremos um degrau a mais de configuração a ser feita e mais código terá em ambas as classes.
