# Sintaxy_SQL_ATV_03

ALTER TABLE alunos ADD COLUMN favorites VARCHAR(3);

UPDATE alunos SET favorites = 'SIM' WHERE ID = 19;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 2;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 10;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 7;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 24;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 4;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 17;
UPDATE alunos SET favorites = 'SIM' WHERE ID = 27;

# Sintaxy_SQL_ATV_04
SELECT nome
FROM AlunosSala.alunos
WHERE favorites = 'SIM'
LIMIT 10;
