# 🎓 Sistema de Matrículas Universitário

## 📌 Descrição

Este projeto tem como objetivo modelar um sistema de matrículas para uma universidade, permitindo o gerenciamento de disciplinas, cursos, alunos e professores, além do processo de matrícula e integração com o sistema de cobrança.

---

## 🧩 Diagrama de Casos de Uso

O sistema foi modelado utilizando UML com um diagrama de casos de uso contendo os seguintes atores:

* Aluno
* Professor
* Secretaria
* Sistema de Cobrança

O diagrama representa as interações entre os usuários e o sistema, incluindo matrícula, cancelamento e gestão acadêmica.

---

## 👤 Histórias de Usuário

### Aluno

* Realizar login
* Consultar disciplinas disponíveis
* Matricular-se em disciplinas obrigatórias (até 4)
* Matricular-se em disciplinas optativas (até 2)
* Cancelar matrícula
* Visualizar matrículas

### Professor

* Consultar alunos matriculados em suas disciplinas

### Secretaria

* Gerenciar disciplinas
* Gerenciar cursos
* Gerenciar professores
* Gerenciar alunos
* Definir currículo do semestre
* Controlar período de matrículas
* Cancelar disciplinas com menos de 3 alunos
* Encerrar matrículas com mais de 60 alunos

### Sistema

* Validar login
* Notificar sistema de cobrança

### Sistema de Cobrança

* Receber dados de matrícula

---

## ⚙️ Regras de Negócio

* Um aluno pode se matricular em até:

  * 4 disciplinas obrigatórias
  * 2 disciplinas optativas
* Uma disciplina só será ofertada se tiver pelo menos 3 alunos matriculados.
* O número máximo de alunos por disciplina é 60.
* Após matrícula, o sistema de cobrança deve ser notificado.
* Todos os usuários devem autenticar com login e senha.

---

## 🛠️ Tecnologias (caso venha a ser implementado)

* Linguagem: a definir
* Banco de Dados: a definir
* UML para modelagem

---

## 📎 Autor

Projeto desenvolvido para atividade acadêmica.
