Primeira Aula de Git e GitHub

📌 Introdução

Bem-vindo à primeira aula do curso de Git e GitHub na ETE Cícero Dias! Neste módulo inicial, você aprenderá os conceitos fundamentais do Git, um sistema de controle de versão distribuído, e do GitHub, uma plataforma para hospedagem de repositórios.

📖 Conteúdo da Aula

Nesta aula, abordaremos os seguintes tópicos:

O que é o Git e por que usá-lo?

Instalação e configuração do Git

Conceitos básicos: repositórios, commits, branches

Criando seu primeiro repositório local

Conectando-se ao GitHub

Enviando seu primeiro commit para o GitHub

🛠 Pré-requisitos

Antes de começar, certifique-se de ter:

Um computador com acesso à internet

Git instalado (Baixe em: https://git-scm.com/)

Uma conta no GitHub (https://github.com/)

🔥 Primeiros Passos

Configurar o Git

git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"

Criar um repositório local

mkdir meu-projeto
cd meu-projeto
git init

Adicionar um arquivo ao repositório

echo "# Meu Primeiro Repositório" > README.md
git add README.md
git commit -m "Primeiro commit"

Enviar para o GitHub

Crie um repositório no GitHub

Conecte o repositório remoto:

git remote add origin https://github.com/seuusuario/meu-projeto.git
git branch -M main
git push -u origin main

📌 Conclusão

Parabéns! Agora você já sabe os conceitos básicos para começar a versionar seus projetos com Git e GitHub. Nas próximas aulas, aprofundaremos o uso de branches, merges, pull requests e outras práticas essenciais.

🚀 Bons estudos!