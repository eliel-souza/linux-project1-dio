# Curso Linux Projeto 1

## Script de criação de estrutura de usuários, diretórios e permissões

Neste projeto foi desenvolvido um script que criasse uma infraestrutura de usuários, grupos de usuários, diretórios e permissões.

Para isso, tinhamos algumas definições:

- O dono de todos os diretórios criados será o usuário root;
- Todos os usuários terão permissão total dentro do diretório publico;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem;

### Diretórios

1. /publico
2. /adm
3. /ven
4. /sec

### Grupos

1. GRP_ADM
2. GRP_VEN
3. GRP_SEC

### Usuários

| GRP_ADM | GRP_VEN    | GRP_SEC  |
| ------- | ---------- | -------- |
| carlos  | debora     | josefina |
| maria   | sebastiana | amanda   |
| joao    | roberto    | rogerio  |

### Permissões

| GRP_ADM  | GRP_VEN  | GRP_SEC  |
| -------- | -------- | -------- |
| /publico | /publico | /publico |
| /adm     | /ven     | /sec     |