# Data Warehouse
Banco de dados utilizado para armazenar informações relativas às atividades de uma organização, possibilitando a análise de grandes volumes de dados - coletados
a partir de sistemas transacionais (OLTP - *Online Transaction Processing*)

- Organizado para dar suporte à tomada de decisões estratégicas da empresa
- Ponto central da infraestrutura de *Business Intelligence*

![esquema-dw](https://www.cetax.com.br/blog/wp-content/uploads/2016/04/Data-Warehouse-Including-Basics.png)

## Características
- Orientado ao negócio
- Não volátil
- Variante no tempo

## OLTP | Data Warehouse | Data Marts | Business Intelligence
![oltp-dw-dm-bi](https://panoply.io/uploads/versions/diagram8-1---x----750-376x---.jpg)


### OLTP x Relatórios Analíticos
- OLTP
  - Informação para suportar decisões diárias
  - Armazenamento em nível de transação
  - Design do banco de dados: normalizado
- Relatórios Analíticos
  - Informação histórica consolidada
  - Integração de diferentes fontes
  - Design do banco de dados: desnormalizado - Star Schema

  
## Quando usar DW?
Necessidade de consolidar dados mais relevantes para a geração de relatórios de BI e suporte à tomada de decisão
- Estrura de dados complexa
- Requerimento de informação consolidada
- Dados dispersos
- Seleção de informações relevantes


## Vantagens
- Informação controlada e confiável
- Qualidade dos dados
- Fonte única de informação
- Dados possuem representação e significado
- Facilidade no controle de acesso e permissões

## Desvantagens
- Dificuldade em coletar e transformas os dados de fontes diversas - atividade essencial na construção do DW
- Problemas de segurança e privacidade - diferentes políticas para acesso dos dados
- Implementação e manutenção dificultada pela constante atualização das tecnologias - complexo e caro
