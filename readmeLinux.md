# VerdanadeskApp - v.1.4.16

É uma aplicação para facilitar a vida de usuários de GLPi, trazendo inovação e uma melhor experiência para o usuário do sistema.

- Fácil
- Rápido
- ✨Mágico✨

## Features

- Abertura de chamado em sua instância GLPI.
- Acompanhamento de seus chamados.
- Criação de acompanhamentos em seus chamados.
- Aprovação de solução diretamente no aplicativo.
- Resposta de pesquisa de satisfação. 
- Autenticação Google e Microsoft.

#### 🔧 Instalação Linux

Para instalação no Linux precisamos de um arquivo [.deb](https://github.com/verdanatech/App-Verdanadesk/releases/download/1.4.16/appdesk-1.4.16.deb) do App.
Após o download o processo de instalação é bastante simples podendo ser feito pela linha de comando ou diretamente com o gerenciador de pacotes do Linux.

###### Configuração
Após a instalação, é preciso configurar os dados da instância GLPI.

- Para configuração mais fácil, basta criar um arquivo .sh com a seguinte estrutura.
```sh
#!/bin/bash 
 mkdir  /etc/verdanadeskapp/
 touch /etc/verdanadeskapp/verdanadeskapp.conf
 echo APP_TOKEN="Url da Instância GLPi" >> /etc/verdanadeskapp/verdanadeskapp.conf
 echo API_URL="Token da API" >> /etc/verdanadeskapp/verdanadeskapp.conf
```
- Após a criação do arquivo .bat basta executá-lo e seu aplicativo estará pronto para uso.


- Como recuperar o api token ?
Passo 1
Acessar o menu: Configurar e clicar em Geral:
![alt text](https://raw.githubusercontent.com/verdanatech/App-Verdanadesk/master/assets/img/passo1.png)
Passo 2
Na aba API, clique no botão Adicionar cliente de API:
![alt text](https://raw.githubusercontent.com/verdanatech/App-Verdanadesk/master/assets/img/passo2.png)
Passo 3
Na janela de Cliente de API, preencha os campos indicados nos infográficos com os números de 1 a 4, depois clique no botão Re-gerar para gerar um novo código Token e finalize clicando no botão Salvar:
![alt text](https://raw.githubusercontent.com/verdanatech/App-Verdanadesk/master/assets/img/passo3.png)

#### 📌  Compatibilidade
- Distribuição Linux Baseadas em Debian

 ## Verdanatech Soluções em TI
[Verdanatech](https://verdanatech.com)
[Verdanadesk](https://verdanadesk.com)