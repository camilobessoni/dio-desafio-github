# Desafio de Projeto - Git/GitHub

* Treinando o Git/GitHub
- noções básicas de Git/GitHub
  
  * sugestão de curso: Introdução ao Git e ao GitHub

- Git devidamente instalado (usaremos o Git Bash)

- Engajamento e vontade de aprender

## Como gerar chave ssh

Os passos abaixos estão detalhados em https://docs.github.com/en/authentication/connecting-to-github-with-ssh

### gerando chave ssh para o usuário "camilobessoni@gmail"

$ ssh-keygen -t ed25519 -C camilobessoni@gmail.com

### consultando a chave ssh pública

$ cd /c/Users/Camilo/.ssh/
$ cat id_ed25519.pub

### iniciando o agente ssh

$ eval $(ssh-agent -s)

### adicionando a chave ssh privada ao agente ssh

$ ssh-add id_ed25519
