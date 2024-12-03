# Cronograma de Atividades

Diagrama criado com base em: <a href="https://app.clickup.com/9011667057/v/g/8cj683h-411">Diagrama de Gantt</a>

| **Atividade** | **Duração (dias)** | **Dependências** |
| --- | --- | --- |
| T1 - Definir escopo | 1 | - |
| T2- Definir funcionalidades a serem desenvolvidas | 1 | T1 (M1) |
| T3 - Desenvolver registro, login de usuário no backend | 5 | T2 (M2) |
| T4 - Desenvolver CRUD de loja no backend | 4 | T3 (M3) |
| T5 - Desenvolver sessão de login e registro do usuário | 4 | T3 (M3) |
| T6 - Desenvolver CRUD de produtos no backend | 8 | T4 (M4) |
| T7 -  Desenvolver tela de loja | 8  | T4, T5 (M5) |
| T8 - Desenvolver tela de produtos | 8 | T6, T7 (M6) |
| T9 - Criar testes no backend | 8  | T3, T4, T6 (M7) |
| T10 - Desenvolver tela de Home no mobile | 8 | T7, T8 (M8) |
| T11 - Deploy backend | 8 | T9 (M9) |
| T12 - Criar testes no mobile | 7 | T10 (M10) |
| T13 - Gerar build do app | 2 | T12 (M11) |
