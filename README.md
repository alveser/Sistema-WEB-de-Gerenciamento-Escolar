# Sistema-WEB-de-Gerenciamento-Escolar
Sistema WEB de Gerenciamento Escolar que cria cronogramas de aulas para os professores

# Integrantes

Hemerson Lopes Barros Braga 

Glaucia Alves e Silva 

Douglas Fernando Gonçalves 

Evandro Ribeiro Alves 

Jessica Batista Teixeira

Igor da Costa Silveira Pestana 

Gillian Ferreira dos Santos Rocha 

Pablo Leandro Pippi

Instalação do Programa

#Server
1.Instalar o Wamp Server
- Entrar no Google Drive https://drive.google.com/drive/folders/1OkJu3Y4nvVREX7sPR50_Yx6gAoKZpzSm?usp=sharing
- Duplo click no arquivo "wampserver3.30_x64"

2.Iniciar Wamp Server.
- Acessar o servidor: http://localhost/phpmyadmin/

3.Fazer o login no servidor.
- Acesse http://localhost/phpmyadmin/
- Dados para login:
- Utilizador: root
- Palavra-passe: *campo vazio

#Data Base

1.Criação do banco de dados.
- Acesse http://localhost/phpmyadmin/
- Acesse a aba "Importar"
- Clicar em "Escolher Arquivo"
- Selecionar o arquivo "sistemaBd.sql" no diretório do sistema "Banco"
- Clicar em "Importar"

2. Criação do super usuário.
- Entrar na tabela "user"
- Entrar na aba "Inserir"
- Definir usuário como "Administrador"
- Definir email como "root"
- Definir senha "1234"
- Clicar em continuar

#Sistema Web

1. Copiar o sistema para o diretório padrão do Wamp Server
- Copiar o diretório "Sistema Cronograma"
- Colar no diretório do Wamp Server em "C:\wamp64\www"
- Alterar o nome do diretório para "Sistema"

2. Alteração no servidor PHP
- Entrar no diretório "C:\wamp64\bin\apache\apache2.4.5.4.2\bin"
- Abrir o arquivo "php.ini"
- Modificar a linha 492 "error_reporting = E_ALL" para "error_reporting = none"
- Reiniciar o servidor

3. Executar o sistema
- http://localhost/sistema
- Dados para login:
- User: root
- Password: 1234

Parte de visualização

A aplicação de Sistema de Gerenciamento Escolar tem como principal objetivo ser uma 
ferramenta completa que gerencie, de forma integrada, todos os recursos necessários para o 
planejamento, execução e monitoramento de atividades escolares. Esta aplicação tem como 
público-alvo secretarias, setores pedagógicos de escolas de ensino regular e profissionalizante. 

Nossa aplicação possui:

• Tela de login

• Tela de Dashboard Gerencial

• Tela de cadastro

• Tela de relatório

• Tela do professor

• Tela de configuração do usuário

