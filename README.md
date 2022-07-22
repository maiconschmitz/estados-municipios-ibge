# estado-cidade-ibge

O repositório **estado-cidade-ibge** contém uma lista atualizada dos Estados e Cidades do Brasil.

São **27** Estados e **5.570** Cidades.

A base de dados utilizada para gerar os dados aqui contidos, é a da versão mais recente disponível no FTP do IBGE, nomeada **DTB_2021.zip**, com última atualização em **22/02/2022**.

A mesma pode ser obtida no seguinte endereço FTP:
[ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2021](ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial/2021 "Cidades e Estados").

Também é possível consultar as informações dos Estados e Cidades (municípios), utilizando o seu Nome ou Código, através da ferramenta [IBGE | Brasil em Síntese](https://cidades.ibge.gov.br/brasil/panorama "IBGE | Brasil em Síntese")

## Formatos disponíveis

### SQL

Script SQL [**estado_cidade_ibge.sql**] compatível com MySQL, responsável por efetuar a criação e inserção dos dados de Estados e Cidades nas respectivas tabelas.

### CSV

São 2 arquivos no formato CSV, contendo respectivamente as listas de Estados e Cidades.

- **estado_ibge.csv** - Lista de Estados
- **cidade_ibge.csv** - Lista de Cidades

## API do IBGE

O IBGE possui uma [API de localidades](https://servicodados.ibge.gov.br/api/docs/localidades "API de localidades"), a qual disponibiliza uma série de recursos e dados tais como: países, regiões do Brasil (Norte, Nordeste, Sudeste, Sul e Centro-Oeste), Unidades da Federação (estados), municípios, microrregiões, mesorregiões, regiões imediatas e intermediárias.

API de localidades: [https://servicodados.ibge.gov.br/api/docs/localidades](https://servicodados.ibge.gov.br/api/docs/localidades "API de localidades").