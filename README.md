# localhost
Toturial para a crição de um servidor FiveM em localhost compatível com qualquer framework. Estes são os ficheiros usados no tutorial.

Tutorial: https://www.twitch.tv/videos/655370057

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

-Instruções:

1- Gerar uma key introduzindo o teu IP e selecionando a opção Home Hosted (para Localhost! No caso de queres uma key para o teu servidor público deves selecionar uma das outras opções, sendo que os sevidores alojados na Zap-hosting não necessitam de uma key.)
https://keymaster.fivem.net/
Para isso deves criar uma conta em https://forum.cfx.re

Em alternativa aos passos 2, 3, 4, 5 e 7.1 podes fazer o download da pasta FXServer e arrastar-la para o teu ambiente de trabalho e avançar para o passo número 6.
https://drive.google.com/file/d/10fM1_Nkm90W4WS2XkUp6Pv7blDc-w76S/view?usp=sharing

2- Cria a pasta "FXServer" no teu ambiente de trabalho 

3- Extrai o conteúdo dos "Artifacts" para dentro da "FXServer" de modo a que os ficheiros fiquem na raiz da pasta.

4- Extrai a pasta "Resources" para dentro da "FXServer" de modo a teres a pasta "resources" dentro da "FXServer", ou seja, "FXServer/resources".

5- Coloca o server.cfg dentro da pasta "FXServer", ou seja, FXServer/server.cfg

6- Edita o ficheiro server.cfg adicionando a tua key gerada no primeiro passo, e a Steam apikey em https://steamcommunity.com/dev/apikey , também aqui escolhes o nome e tags para o teu servidor entre outras coisas.

7.1 Abre o bloco de notas e cria um ficheiro com o nome "run" e a extenção ".cmd" e adiciona esse texto. 

7.2 Deves substituir o XXXXXXXXX pelo nome do teu utilizador. Para saberes isso podes abrir as propriedades de qualquer ficheiro no teu ambiente de trabalho e verás lá o nome correto na Localização.

Conteúdo do "run.cmd":

cd C:\Users\XXXXXXXXX\Desktop\FxServer
C:\Users\XXXXXXXXX\Desktop\FxServer\FXServer.exe +exec server.cfg

8- Abrir o "FXServer.exe" seguido do "run.cmd". Abres o FiveM e na aba History escreves localhost.

9- Have Fun
