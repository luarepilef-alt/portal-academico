# Modelo do banco de dados

Diagrama entidade-relacionamento do Portal Acadêmico.

## Entidades principais

- **Usuario**: alunos, professores e admins (diferenciados pelo campo `papel`)
- **Curso** e **Disciplina**: estrutura acadêmica
- **Turma**: uma oferta de uma disciplina em um semestre, com um professor responsável
- **Matricula**: liga um aluno a uma turma (resolve o relacionamento muitos-para-muitos)
- **Nota** e **Frequencia**: penduradas na Matricula, permitindo várias notas por avaliação

## Diagrama

<img width="1168" height="855" alt="DER_PROETOAC" src="https://github.com/user-attachments/assets/8995966b-2ff1-4f61-9e6a-a3895f3541af" /

