# modelagem-de-dados
Projeto individual de modelagem e criação de um banco de dados utilizando MySQL.

Trabalho acadêmico com a proposta de desenvolver um banco de dados para um colégio. Durante o projeto foi desenvolvido um modelo lógico, conceitual e o própio banco no MySQL.

Sobre o banco de dados:

  - Existem outras entidades além dessas três (curso, turma e aluno)? Sim.
  Entidades que se encontram no modelo proposto são:
    1. Curso
    2. Turma
    3. Disciplina
    4. Aluno
    5. Professor
    
  - Quais são os principais campos e tipos?
  Os principais campos que distinguem as entidades são as chaves primárias(PK) representadas pelas colunas com o prefixo cod:
    1. cod_Curso
    2. Cod_Turma
    3. Cod_Aluno
    4. Cod_Prof
    5. Cod_Disc
    
  Estas chaves são códigos únicos utilizadoas também para um possível referenciamento em outra tabela, assumindo o papel de chave estrangeira(FK). No modelo lógico é possível ver as tabelas, suas respectivas chaves e o tipo de dado a ser recebido.
  ![image](https://user-images.githubusercontent.com/112870328/214409731-ee2da6ab-ca7a-407f-8892-93ade3dd159e.png)
  
  - Como estas chaves estão relacionadas?
    Curso tem turma,
    turma possui disciplina,
    disciplina possui professor que comanda a turma,
    aluno pertence a turma.
