FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt update && sudo apt install -y git && git clone https://github.com/kleytonfernandes135-commits/instalador40.git install && cd ./install && sudo chmod +x ./install_primaria ./install_instancia && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO):

```bash
cd ~/install && sudo ./install_instancia
```

TOKEN DO GITHUB

O token NUNCA fica gravado no código. Durante a instalação o instalador pergunta o
link do repositório (ENTER usa o padrão definido em `variables/_app.sh`) e o token
(digitação oculta; deixe vazio se o repositório for público).

Para não digitar, exporte antes de rodar:

```bash
export ZAPSTART_GIT_TOKEN=seu_token
sudo -E ./install_primaria
```
# instalador40
# instalador40
