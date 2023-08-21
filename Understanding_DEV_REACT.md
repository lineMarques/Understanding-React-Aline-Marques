---
# Guia Básico Git e GitHub

Crie uma conta no GitHub

[www.github.com](www.github.com)

## Configure e-mail e usuario no git

A configuração a nível global (para a máquina toda)

```>git config --global user.name "Seu nome de usuario"```

```>git config --global user.email "Seu nome de email"```

A configuração a nível local (apenas para o projeto)

```>git config --local user.name "Seu nome de usuario"```

```>git config --local user.email "Seu nome de email"```

## Criando um novo repositório local

Crie uma nova pasta, abra-a e execute o comando,

```> git init```

Adicione um conteúdo específico do diretório no git

```>git add nome_do_arquivo```

Adicione todo o conteúdo do diretório de uma só vez no git

```>git add .```

Para rastrear as modificações

```>git commit -m 'comentário'```

Para fazer um link entre seu repositório local e o gitHub

```>git remote add origin link-do-repositório-do-github```

## Enviando as alterações para o GitHub

Para enviar pela primeira vez

```>git push -u origin main```

Para as próximas vezes

```>git push```

## Para copiar um repositório

```>git clone link_do_repositório_que_deseja_copiar```

## Para atualizar o repositório local

```>git pull```

## Para vizualizar o histórico das alterações

```>git log```


---
