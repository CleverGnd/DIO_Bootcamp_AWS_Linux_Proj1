# Bootcamp Cloud AWS da DIO - Desafio de Projeto 1 Linux
Este repositório foi criado para o versionamento e apresentação do Desafio de Projeto 1 desenvolvido no Bootcamp Cloud AWS da DIO.

Unidade: Conhecendo o Sistema Operacional Linux <br>
Professor: [Denilson Bonatti](https://github.com/denilsonbonatti/)

<a href="https://www.dio.me/bootcamp/bootcamp-cloud-aws"><img src="https://hermes.digitalinnovation.one/tracks/af22d4a0-463f-48c5-a70c-4961d5e618d0.png" align="center" height="120" width="120" ></a> <a href="https://www.dio.me/"><img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" align="center" height="120" width="120" ></a> <br>

## Configurando Permissões e Usuários em Linux
Script bash que pode ser utilizado para configurar permissões e usuários em um sistema operacional Linux.

### Como usar
    1 - Clone o repositório para sua máquina local.
    2 - Abra o terminal com o usuário root e navegue até a pasta em que o repositório foi clonado.
    3 - Abra um terminal no diretório onde você salvou o arquivo.
    4 - Execute o comando "chmod +x create_user_data.sh" para tornar o arquivo executável.
    5 - Execute o comando "./create_user_data.sh" para executar o script.
    6 - Aguarde a conclusão da execução do script.

### O que o script faz
O script cria os seguintes diretórios: /publico, /adm, /ven e /sec. <br>
Em seguida, cria os seguintes grupos de usuários: GRP_ADM, GRP_VEN e GRP_SEC.

Também cria os seguintes usuários:
| Usuário | Nome Completo | Grupo |
| ----- | ----- | ----- |
| carlos | Carlos | GRP_ADM |
| maria | Maria | GRP_ADM |
| joao | João | GRP_ADM |
| debora | Debora | GRP_VEN |
| sebastiana | Sebastiana | GRP_VEN |
| roberto | Roberto | GRP_VEN |
| josefina | Josefina | GRP_SEC |
| amanda | Amanda | GRP_SEC |
| rogerio | Rogério | GRP_SEC |

Obs: Senha padrão para todos os usuários "Senha123"

Por fim, define as seguintes permissões: <br>
O grupo GRP_ADM é o proprietário do diretório /adm. <br>
O grupo GRP_VEN é o proprietário do diretório /ven. <br>
O grupo GRP_SEC é o proprietário do diretório /sec.

O diretório /adm, /ven e /sec têm permissões 770. <br>
O diretório /publico tem permissões 777.

O script é útil para quem precisa configurar várias permissões e usuários em um sistema operacional Linux.
