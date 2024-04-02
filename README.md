# Sintaxy_SQL_ATV_03

ALTER TABLE alunos ADD COLUMN favorites VARCHAR(3);
UPDATE alunos SET favorites = 'SIM' WHERE ID = 19;


# Sintaxy_SQL_ATV_04
SELECT nome
FROM AlunosSala.alunos
WHERE favorites = 'SIM'
LIMIT 10;
