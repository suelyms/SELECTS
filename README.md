# SELECTS
Códigos para consultas

## SELECT * FROM tbven; ##

-- Lendo o comando: Seleciona todas as colunas da tabela: tbven e seus respectivos registros (linhas)

## SELECT * FROM tbven_item;

-- Lendo o comando: Seleciona todas as colunas da tabela: tbven_item e seus respectivos registros (linhas)

## SELECT * FROM tbpro;

-- Lendo o comando: Seleciona todas as colunas da tabela: tbpro e seus respectivos registros (linhas)

## SELECT * FROM tbvdd;

-- Lendo o comando: Seleciona todas as colunas da tabela: tbvdd e seus respectivos registros (linhas)

## SELECT * FROM tbdep;

-- Lendo o comando: Seleciona todas as colunas da tabela: tbdep e seus respectivos registros (linhas)

-- Warning: Evite o uso do *, seja específico, adicione apenas as colunas que irá precisar na sua análise.

-- Exemplo:

 SELECT estcli AS Estado,
  cidcli AS Cidade
  FROM tbven; 
  
-- Lendo o comando: Seleciona as colunas: estcli (Alias: Estado) e cidcli (Alias: Cidade) da tabela: tbven



