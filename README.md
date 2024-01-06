# RECIPES - Site de Receitas
Bem-vindo ao Recipes, um projeto desenvolvido em Python com o framework Django para criar um site de receitas interativo e envolvente. Este projeto permite que os usuários visualizem, compartilhem e contribuam com suas receitas favoritas.

### Como começar
Siga estas instruções para configurar e executar o projeto localmente em seu ambiente de desenvolvimento.

### Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina. Recomendo a utilização de um ambiente virtual para isolar as dependências do projeto.

`pip install virtualenv`

<hr>

## Instalação

### Clone este repositório:
`git clone https://github.com/beniciodev/SiteDeReceitas__Django.git`

`cd SiteDeReceitas__Django` 

###  Crie um ambiente virtual e ative-o:
`py -m virtualenv venv`

`source venv/bin/activate`  

##### No Windows: 

`venv\Scripts\activate`

### Crie um superuser para acessar o painel de administração

`python manage.py createsuperuser`


<hr>


### Inicie o servidor de desenvolvimento:
`python manage.py runserver`

- O site estará disponível em http://localhost:8000/. 

- O painel de administração pode ser acessado em http://localhost:8000/admin/.

