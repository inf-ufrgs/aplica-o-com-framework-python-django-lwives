[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ceqLrro5)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23737796)
# Instruções 

## Etapa 1: Preparação do Ambiente

Abra o repositório no CodeSpaces (via Classroom). Para tanto, clique no botão "Code" no repositório do GitHub e selecione a aba "Codespaces" > "Create codespace on main".

Ele irá clonar o repositório em um espaço só seu, privado, e abrir um ambiente virtual com Linux e o editor VS Code. Nele, realize as tarefas e, ao terminar, faça um push para sincronizar seu trabalho com o repositório, e o professor será avisado e poderá conferir. 

Se desejar rodar no seu computador local, clone o repositório localmente e, depois, suba o ambiente via terminal (é necessário ter o Docker previamente instalado): docker-compose run --rm web bash.

## Etapa 2: Instalação do Framework 

Basicamente, você deve:

1. Criar um ambiente virtual: python -m venv .venv
2. Ativar o ambiente: source .venv/bin/activate
3. Instalar o Django: python -m pip install Django

## Etapa 3: Criando o Projeto e a App (Tutorial 01)

Siga a documentação oficial disponível em https://docs.djangoproject.com/pt-br/6.0/intro/tutorial01/.

Ela envolve:
1. Criação do Projeto: django-admin startproject mysite.
2. Verificação (rodar o servidor pela primeira vez): python manage.py runserver 0.0.0.0:8000.
3. Criação da App "Polls": python manage.py startapp polls.
4. Seguir os demais passos (até a etapa 8) - não precisa fazer a partir da etapa 9.

**Atenção**: Ao executar `python manage.py runserver`, o VS Code no navegador mostrará uma notificação no canto inferior direito: "Your application running on port 8000 is available.". Clique em "Open in Browser" e a aplicação aparecerá.

## Entrega

**Não esqueçam de salvar os arquivos e, ao terminar, fazer `commit` para que as suas modificações sejam refletidas no repositório!**

Se precisar, solicite ajuda ao professor.
