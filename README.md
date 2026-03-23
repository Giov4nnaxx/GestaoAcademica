# 🎓 Sistema de Gestão Acadêmica

## 📌 Descrição
Sistema desenvolvido para gerenciamento acadêmico, permitindo o cadastro, edição e consulta de informações.

## 💻 Tecnologias utilizadas
- Java / JavaScript (coloca o que você usou)
- MySQL (se tiver)
- HTML, CSS

## 🚀 Funcionalidades
- Cadastro de alunos
- Listagem de dados
- Edição de informações
- Exclusão de registros

## 🎯 Objetivo
Projeto desenvolvido com foco em praticar lógica de programação, estrutura de dados e desenvolvimento de sistemas.

## ▶️ Como executar
(Se quiser, coloca como roda) ┣ 📄 Aluno.java           → Entidade Aluno
 ┣ 📄 Turma.java           → Entidade Turma
 ┣ 📄 AlunoService.java    → Regras e operações de alunos
 ┣ 📄 TurmaService.java    → Regras e operações de turmas
```

---

## 🔄 Organização do Código

O sistema segue o princípio de **separação de responsabilidades (SRP)**:

* `Main`: responsável apenas pela interação com o usuário
* `AlunoService`: contém toda a lógica relacionada aos alunos
* `TurmaService`: contém toda a lógica relacionada às turmas

---

## ⚙️ Conceitos Aplicados

* Encapsulamento
* Separação de responsabilidades
* Regras de negócio
* Validação de dados
* Uso de lambdas e Stream API
* Soft delete (desativação em vez de remoção)

---

## 💡 Melhorias Implementadas

* Filtro de alunos por turma
* Verificação de alunos ativos antes de desativar turma
* Uso de `anyMatch` para validações
* Uso de `forEach` para operações em lote
* Validação de idade com `Period`
* Código mais limpo com métodos reutilizáveis

---

## 🚀 Possíveis Evoluções

* Interface gráfica (JavaFX ou Swing)
* Persistência em banco de dados
* API REST (Spring Boot)
* Sistema de login
* Relatórios acadêmicos

---

## 📚 Objetivo do Projeto

Este projeto foi desenvolvido com fins educacionais para prática de:

* Lógica de programação
* Estruturação de sistemas
* Boas práticas em Java
* Simulação de regras reais de negócio

---

## 👩‍💻 Autora

Desenvolvido por **Giovanna Santana**
