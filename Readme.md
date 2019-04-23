# Github
 
![Logo](https://github.com/favicon.ico)
Primeiro Projeto usando controle de Versão   
Ajuda: [Git](https://git-scm.com/doc)

## Configuração
### Configurações Globais

```git config --global user.name "Etec Antonio Devisate"```   
```git config --global user.email "etec@devisate.com.br"```     

### Configurações Locais (Diretório do Repositório)

```git config  user.name "Etec Antonio Devisate"```   
```git config  user.email "etec@devisate.com.br"```   

### Visualizando as configurações

```git config --list ```   
```git config user.name```   
 
#### Não salvar as credenciais no Windows
```git config  --system --unset credential.helper```   

## Comandos

Comando             |   Resultado
--------            |   ----------
git init            |   Inicializa um repositório
git add             |   Adiciona o arquivo
git status          |   Status do arquivo
git commit          |   Efetua o commit
git log             |   Exibe os logs do commit
git shortlog        |   Exibe os logs de forma resumida
git shortlog -sn    |   Quantidade de logs
git diff            |   Exibe as modificações feitas no arquivo antes de efetuar o commit
git tag             |   Lista as tags existentes
git tag -a 1.0 -m "Descrição da Tag" | Cria a tag 1.0
