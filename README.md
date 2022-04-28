# estado-cidade-ibge

O repositório **estado-cidade-ibge** contém uma lista de Estados e Cidades do Brasil.

São **27** Estados e **5.570** Cidades.

A base de dados utilizada para gerar os dados aqui contidos, é a da versão mais recente disponível no FTP do IBGE, nomeada **DTB_2019_v2.zip**, com última atualização em **07/07/2020**.

A mesma pode ser obtida no seguinte endereço:
[ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2019](ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2019 "Cidades e Estados").

É possível também, consultar tais cidades (municípios), através do seu Nome ou Código, no seguinte link:
[Brasil | Cidades e Estados | IBGE](https://www.ibge.gov.br/cidades-e-estados.html?view=municipio "Cidades e Estados")

## SQL

O Script SQL (**estado_cidade_ibge.sql**), é compatível com MySQL e efetua a criação, bem como a inserção dos conteúdos de Estados e Cidades nas respectivas tabelas.

## CSV

São 2 arquivos no formato CSV, contendo respectivamente, a lista de Estados e Cidades.

**estado_ibge.csv** - Lista de Estados

**cidade_ibge.csv** - Lista de Cidades
