# Craftcode website


## Instalação (uma única vez)
Depois que baixar o repositório, faça o seguinte para instalar o ambiente na sua máquina
 1. Primeiro instale o virtualenv
 ~~~shell
 apt install virtualenv
 ~~~
 2. Crie um ambiente virtual 
 ~~~shell
 virtualenv -p python3 venvcc
 ~~~
 3. Inicie o ambiente virtual
 ~~~shell
 source venvcc/bin/activate
 ~~~
 4. Instale as dependências
 ~~~shell
 pip install django
 ~~~
 5. Execute as migrations
 ~~~shell
 cd 
 ~~~

## Iniciar o app (todas as vezes que for iniciar a aplicação localmente)