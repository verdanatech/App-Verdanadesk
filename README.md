# App Verdanadesk - v.1.4.16

É uma aplicação para facilitar a vida de usuários de GLPi, trazendo inovação e uma melhor experiência para o usuário do sistema.

Desenvolvemos este aplicativo com o intuito de melhorar o nível de relacionamento do seu cliente com a Central de Serviços. Onde o usuário pode registrar suas demandas de forma fácil e rápida sem precisar acessar o navegador de internet e receber as notificações direto no seu Desktop. 

O aplicativo está disponível para Windows e Linux.

- Fácil
- Rápido
- ✨Mágico✨

#### 📌  Compatibilidade
- Windows 10
- Windows 11

## Features

- Abertura de chamado em sua instância GLPI.
- Acompanhamento de seus chamados.
- Criação de acompanhamentos em seus chamados.
- Aprovação de solução diretamente no aplicativo.
- Resposta de pesquisa de satisfação. 
- Autenticação Google e Microsoft.

#### 🔧 Instalação Windows

Para instalação no Windows precisamos de um [MSI](https://github.com/verdanatech/App-Verdanadesk/releases/download/1.4.16/appdesk-1.4.16.msi) ou [EXE](https://github.com/verdanatech/App-Verdanadesk/releases/download/1.4.16/appdesk-1.4.16.exe) do App.
Após o download o processo de instalação é bastante simples basta seguir os passos de instalação do Windows.

###### Configuração
Após a instalação, é preciso configurar os dados da instância GLPI.

- Para configuração mais fácil, basta criar um arquivo .bat com a seguinte estrutura.
```sh
reg add hklm\software\verdanadeskapp /v api_token /t REG_SZ /d Token da API /f
reg add hklm\software\verdanadeskapp /v api_url /t REG_SZ /d Url da Instância GLPI /f
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


 ## Verdanatech Soluções em TI
- [Verdanatech](https://verdanatech.com)
- [Verdanadesk](https://verdanadesk.com)
