


Baixe do meu repositokrio os arquivos https://github.com/ronilsonreis/Micropython/
Neste arquivo contém:
putty.exe
ESPlorer.zip
webrepl-master.zip
ESP8266Flasher.exe obter a versão mais
Vamos precisar também do arquivo esp8266-20171101-v1.9.x.bin que pode ser baixado de https://micropython.org/download  é importante sempre obter a versão mais atualizada do arquivo.

Após baixar todso so arquivos 
conecte-se ao ESP8266 via serial.
1 - Valide no gerenciador de dispositivos subitem Porta COM e LPT se a porta equivalente ao seu NODEMCU connectado está habilitada vide imagem



Caso não esteja instale o CP210x_Windows_Drivers
Assim que seu NODEMCU for habilitado juntamente com a porta abra o arquivo ESP8266Flasher.exe 
em seguida: 
1 - Em "Operation" Selecione a porta equivaelente ao seu dispositivo;
2 - Em "Config" Selecioar o arquivo esp8266-20171101-v1.9.x.bin para instalçao do Micropython no NODEMCU
3 - Em "Advanced" Configurar BAUDRATE para 115200 e manter o restate como está.

Abertura e Config do Putty

Duplo clic no arquivo putty.exe

Configurar 
  1 - Em "serial Line" digitar a a mesma porta selecionada anteriormente e visualizada no Gerenciador de dispositivo.
  2 - Em "Connection Type" Selecionar "Serial" 
  3 - Em "Spedd" digitar 115200
  
  Em Saved Session digirar "Esp8266" clicar em Saved mantenha as outras configurações como estão
  Para inicar a sessão clicar em "Open"
  Será visualizada uma tela totalmente sempre preenchimento, caso ocorra aperte em seu Esp8266 o botão RST m seguida s´erá visualizada o conforme s dados
  
*****************Console do Putty*********************
#L▒#5 ets_task(40100130, 3, 3fff837c, 4)
OSError: [Errno 2] ENOENT

MicroPython v1.9.3-8-g63826ac5c on 2017-11-01; ESP module with ESP8266
Type "help()" for more information.
>>>
****************************************
Dicas!

Caso não consiga digitar no console veja se está como administrador ou se o programa esta aberto em modo admonistrador

Abertura do ESPlorer  - O ESPlorer é uma IDE multiplataforma escrita em Java, criado pela 4refrOnt russa para desenvolver em LUA para nodeMCU e MicroPython e também suporta todos os comandos AT. Infelizmente, por ser Java requer Java SE a partir da versão 7 instalada. Para executar em Linux, pode-se abrir um terminal e ...
Deve ser aberto através do arquivo  ESPlorer.bat
Após abertura 
1 - clicar em settings e selecionar o botão radio de MicroPython
2 - Altrar o BAUDRATE para 115200
3 - Clicar em "Open"
Após clicar não se esqueça de apertar o botão RST do seu NODEMCU
 


  

