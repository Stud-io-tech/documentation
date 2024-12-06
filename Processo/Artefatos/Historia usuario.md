### **Histórias de Usuário**
  
**Fase:** Planejamento  
  
**Descrição:**  
- As **Histórias de Usuário** são descrições de funcionalidades do ponto de vista do usuário final. Elas são criadas a partir do **Contexto** e devem ser pequenas, de fácil compreensão e com critérios de aceitação claros.  
- Cada história de usuário descreve o que o usuário precisa fazer, por que isso é importante e o resultado esperado.  
- Exemplos de histórias de usuário: "Como [usuário], quero [funcionalidade] para que eu possa [benefício]."
  
**Utilidade:**  
- Serve para guiar o desenvolvimento de funcionalidades e garantir que as entregas atendam às necessidades do cliente.  
- As histórias ajudam a priorizar o trabalho, facilitando a organização e execução das atividades.

**Instanciado:**  
- Neste repositório, este artefato está no raíz do diretório [requisitos](/documentacao/requisitos/) com a seguinte padrão de identificação ...

### **Padrão de Identificação para os Requisitos desse Projeto**

#### **Formato Geral**
- Cada requisito terá um identificador único, seguindo uma **estrutura hierárquica**.  
- O formato será: `REQ.<Nível>.<Subnível>.<Subnível...>.md`  
- Artefatos de Requisitos devem ser nomeados conforme o identificador, por exemplo: `REQ.001.md`, `REQ.001.001.md`.

### **Estrutura e Regras**
1. **Nível 1:** Representa o requisito pai, uma funcionalidade, agrupamento mais geral de um conjunto de funcionalidades ou alguma descrição mais abstrata.  
   **Exemplo:**  
   - `REQ.001.md`: "Cadastro de Usuários"  
   - `REQ.002.md`: "Gerar Relatório Mensal"
   - `REQ.003.md`: "Facilidade de Uso"

2. **Níveis subsequentes:** Caso necessite Requisitos de níveis subsequentes, esses derivados finais são os itens entregáveis, tornando os superiores mais abstratos.  
   **Exemplo:**  
   - `REQ.001.001.md`: "Criar Usuário" (filho de `REQ.001.md`)  
   - `REQ.001.002.md`: "Editar Usuário"  

4. **Documentação:** Cada identificador estará associado a um arquivo Markdown (`.md`), contendo:
   - [#Título]
   - {**COMO**  **QUERO**  **PARA**}
   - {## Critério de Aceitação}
 

---

## **Exemplo Prático**
### Arquivo: `REQ.001.md`
```markdown
# Cadastro de Produtos
  
**COMO** Dona do Negócio,   
**QUERO** cadastrar meus produtos no sistema, incluindo nome, descrição, preço e quantidade em estoque,  
**PARA** gerenciar o inventário.

#### Critérios de Aceitação:
1. Deve ser possível cadastrar produtos com campos obrigatórios (nome, preço e quantidade).
2. Deve haver a possibilidade de editar e excluir produtos.
3. Produtos cadastrados devem aparecer no módulo de vendas.
