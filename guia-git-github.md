# Mexendo com Git.

* Criar sua conta aqui no GitHub :)
* Instalar o Git em sua máquina, para windows recomendo baixar do site oficial da ferramenta: https://git-scm.com/downloads, para Mac e Linux, recomendo usar o brew ou o apt-get da vida para instalação


## Versionando um projeto.

Via terminal (prompt de comando ou tela preta da matrix) acesse a pasta do seu projeto.

> cd NOMEDAPASTA (É o comando para acessar pastas via terminal.)

Dentro da pasta do seu projeto digite

```
  git init (agora esta pasta tem o seu código observado pelo Git e todas as alterações podem gerar versões do Código)
```


```
  git add . (adiciona todos os arquivos alterados dentro da pasta para que o git confirme as alterações deles)
```

```
  git commit -m "Mensagem que explica o que foi feito até o momento." (Cria um pacote com as alterações feitas e gera uma nova versão do código)
```
Pronto agora você tem um ponto que pode restaurar o seu código no futuro.

## Por dentro do Github.

Após criar sua conta, encontre a opcão "create new repository".

Informe o nome e a descrição do seu projeto, e agora você tem a pasta virtual do seu projeto.

Com tudo isso pronto, siga os passos que o próprio github sugere para deixar o código da sua máquina guardado no Github.

> git remote (cria uma sincronia da sua pasta local com a pasta virtual)

> git push (faz o código ir da sua máquina local para a pasta virtual no Github)
