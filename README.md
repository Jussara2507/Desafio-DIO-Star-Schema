Desafio DIO - Modelagem Dimensional Star Schema
Objetivo
Desenvolver um modelo dimensional (Star Schema) com foco na análise de professores.

Modelo Desenvolvido
O esquema em estrela foi construído tendo a tabela FATO_DOCENCIA como fato principal.

Tabela Fato
FATO_DOCENCIA
Métricas:

Quantidade de disciplinas ministradas
Carga horária ministrada
Tabelas Dimensão
DIM_PROFESSOR
Informações dos professores.

DIM_CURSO
Informações dos cursos.

DIM_DISCIPLINA
Informações das disciplinas.

DIM_DEPARTAMENTO
Informações dos departamentos.

DIM_DATA
Informações temporais para análises por período.

Relacionamentos
Todas as dimensões estão relacionadas à tabela fato através de relacionamentos 1:N, seguindo o padrão Star Schema.

Ferramentas Utilizadas
Power BI Desktop
Excel
GitHub
Autora
Jussara Santos


