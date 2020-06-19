# localhost
Toturial para a crição de um servidor FiveM em localhost compatível com qualquer framework. Estes são os ficheiros usados no tutorial.


Suporte em português: https://discord.gg/SpERma7


10% de desconto em todos os serviços:
<a href='https://zap-hosting.com/a/992c9e08c563a2b021fbd10fdaf9513838380d56'><img src="https://zap-cdn.com/interface/_images/banner/gameserver/fivem-affiliate-banner-1006x180.png" alt="ZAP-Hosting Gameserver and Webhosting"></a>
Código Promocional: ums18-a-5472


-Documentação:

https://docs.fivem.net/docs/server-manual/setting-up-a-server/


-Ficheiros necessários:

Artifacts:
https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/

Resources:
https://github.com/galves46/cfx-server-data

-Instructions:

1- Gerar uma key introduzindo o teu IP e selecionando a opção Home Hosted (para Localhost! No caso de queres uma key para o teu servidor público deves selecionar uma das outras opções, sendo que os sevidores alojados na Zap-hosting não necessitam de uma key.)
https://keymaster.fivem.net/
Para isso deves criar uma conta em https://forum.cfx.re

2- Cria a pasta "FXServer" no teu ambiente de trabalho 

3- Extrai o conteúdo dos "Artifacts" para dentro da "FXServer" de modo a que os ficheiros fiquem na raiz da pasta.

4- Extrai a pasta "Resources" para dentro da "FXServer" de modo a teres a pasta "resources" dentro da "FXServer", ou seja, "FXServer/resources".

5- Coloca o server.cfg dentro da pasta "FXServer", ou seja, FXServer/server.cfg

6- Edita o ficheiro server.cfg adicionando a tua key gerada no primeiro passo, e a Steam apikey em https://steamcommunity.com/dev/apikey .
7- Abre o ficheiro FXServer.exe e de seguida o run.cmd
