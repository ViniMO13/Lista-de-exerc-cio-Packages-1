# PL/SQL - Sistema de Gerenciamento de Alunos, Disciplinas e Professores

## **Descrição**
Este projeto contém três pacotes PL/SQL desenvolvidos no Oracle para gerenciar as entidades **Aluno**, **Disciplina** e **Professor**. Ele utiliza **procedures**, **functions** e **cursores** para executar operações como exclusão, listagem e cálculos relacionados a essas entidades.

## **Pacotes Implementados**
### **PKG_ALUNO**
- **EXCLUIR_ALUNO:** Remove um aluno e suas matrículas associadas.
- **C_ALUNOS_MAIORES_18:** Lista alunos maiores de 18 anos.
- **C_ALUNOS_POR_CURSO:** Lista alunos matriculados em um curso específico.

### **PKG_DISCIPLINA**
- **CADASTRAR_DISCIPLINA:** Cadastra uma nova disciplina.
- **C_ALUNOS_POR_DISCIPLINA:** Lista disciplinas com mais de 10 alunos.
- **C_MEDIA_IDADE_DISCIPLINA:** Calcula a média de idade dos alunos de uma disciplina.
- **LISTAR_ALUNOS_DISCIPLINA:** Lista os alunos de uma disciplina.

### **PKG_PROFESSOR**
- **C_TURMAS_PROFESSOR:** Lista professores com mais de uma turma.
- **TOTAL_TURMAS_PROFESSOR:** Retorna o total de turmas de um professor.
- **PROFESSOR_DISCIPLINA:** Retorna o nome do professor responsável por uma disciplina.

## **Execução**
1. Instale o Oracle Database.
2. Conecte-se ao banco de dados com um cliente SQL.
3. Execute o arquivo `.sql` fornecido no repositório para criar as tabelas e pacotes.
4. Use os procedimentos, funções e cursores para realizar operações conforme necessário.

## **Estrutura do Repositório**
- `script.sql`: Código completo para criar os pacotes.
- `README.md`: Instruções para uso e descrição do projeto.
