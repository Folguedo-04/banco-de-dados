Tabela ALUNO
Armazena informações básicas dos alunos.

sql
Copiar código



Tabela DISCIPLINA
Guarda informações sobre disciplinas.

sql
Copiar código




Tabela PROFESSOR
Contém dados básicos dos professores.




Tabela MATRICULA
Relaciona alunos e disciplinas, indicando em quais disciplinas um aluno está matriculado.




Tabela TURMA
Relaciona professores e disciplinas, indicando quem leciona cada disciplina.




2. Pacote PKG_ALUNO
Excluir Aluno
Remove um aluno e suas matrículas associadas:






Cursor de Alunos Maiores de 18 Anos
Lista alunos cuja idade é maior que 18 anos:

sql
Copiar código







Cursor com Filtro por Curso
Retorna os nomes dos alunos matriculados em um curso específico:

sql
Copiar código





3. Pacote PKG_DISCIPLINA
Cadastrar Disciplina
Insere uma nova disciplina no banco de dados:





Cursor Total de Alunos por Disciplina
Lista disciplinas com mais de 10 alunos matriculados:

sql
Copiar código





Cursor Média de Idade por Disciplina
Calcula a média de idade dos alunos matriculados em uma disciplina:





Listar Alunos de uma Disciplina
Exibe alunos matriculados em uma disciplina específica:

sql
Copiar código






4. Pacote PKG_PROFESSOR
Cursor Total de Turmas por Professor
Lista professores com mais de uma turma:




Function Total de Turmas de um Professor
Retorna o número total de turmas de um professor:






Function Professor de uma Disciplina
Retorna o nome do professor responsável por uma disciplina:




