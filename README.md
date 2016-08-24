cont(<coluna>)-> conta quantas linhas da coluna

//SELECT count(*) as linhas FROM funcionarios
//SELECT count(*) FROM funcionarios WHERE sexo is NOT NULL.

sum(<coluna>)-> qual coluna voce quer somar
//SELECT sun (salario) + sun (ID) AS total FROM funcionarios

avg(<coluna>)->media da coluna
//SELECT avg (salario) FROM funcionarios

max(<coluna>)->obtem maior valor
//SELECT max (ID) FROM funcionarios
//SELECT max (ID)+1 FROM funcionarios

min(<coluna>)->obtem menor valor
//SELECT min (ID) FROM funcionarios
