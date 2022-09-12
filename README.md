# App Desk

Projeto desenvolvido para usuário verdanadesk, aplicativo para uso do glpi porém com interface mais amigável e simplificada.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e geração de releases.

Consulte **Instalação** para saber como implantar o projeto.

### 📋 Pré-requisitos

De que coisas você precisa para instalar o software e como instalá-lo?

```
- Node.js (versão utilizada 14.17.1)
- Npm
```

#### Install 

```
curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```


### 🔧 Instalação

Para realizar a instalação, seguir os seguintes passos:

```
1) Realizar instalação dos pré-requisitos
2) Executar no terminal (node --version e npm --version)
    - Deve aparecer a versão dos programas, caso não ocorra verificar instalação dos pré-requisitos
3) Clonar repositório em seu ambiente e abrir sua pasta
4) Executar no terminal dentro do diretório da aplicação: npm install
5) Finalizada a instalação, para visualizar o preview pasta executar: npm start
```

## ⚙️ Gerando releases

### :computer: Windows

```
1) Apagar pasta dist
2) No terminal executar os seguintes comandos em ordem:
    - npm run build
    - npm run publish
3) Release será criada no github
4) Basta acessar a release no github e publicar
```

### :computer: Linux

Explique que eles verificam esses testes e porquê.

```
1) Apagar pasta dist
2) No terminal executar os seguintes comandos em ordem:
    - npm run build
    - npm run dist:deb
3) Acessar pasta dist
4) Disponibilizar arquivo deb para usuários
```

## Configuração

### :computer: Linux

```
1) Dentro do diretório '/etc/verdanadeskapp' criar o arquivo verdanadeskapp.conf.
2) Editar o arquivo de acordo com seus dados com o conteúdo abaixo:

APP_TOKEN={{APP_TOKEN}}
API_URL={{URL_BASE}}
```

### :computer: Windows

```
1) Criar uma pasta chamada Verdanadeskapp dentro do Editor do Registro do Windows no caminho '\HKEY_LOCAL\SOFTWARE'.
2) Dentro dessa pasta, criar os arquivos 'api_token' com o seu Token da API e 'api_url', onde vai deve ser adicionado a sua url base.
```

## :warning: Possíveis erros

- ##### Npm start: Arquivo chrome-sandbox
  > **Solução**:
  > <br /> 1) Acessar o diretório node_modules/electron/dist/
  > <br /> 2) Alterar a permissão do arquivo chrome-sandbox para 4755
  > <br /> 3) Alterar o dono arquivo chrome-sandbox para root

## 🛠️ Construído com

- [Electron](https://www.electronjs.org/) - O framework multiplataforma
- [Vue.js](https://cli.vuejs.org/) - Framework para desenvolvimento da interface
- [Vuetify](https://vuetifyjs.com/en/) - Biblioteca UI para Vue.js

## 🖇️ Colaborando

Por favor, leia o [COLABORACAO.md](https://gist.github.com/usuario/linkParaInfoSobreContribuicoes) para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

## 📌 Versão

Nós utilizamos o versionamento do github: [_Releases_](https://github.com/verdanatech/appdesk/releases)
