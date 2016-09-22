# BrinquedoIOT_Free

CAB - Controle Arduino Bluetooth


Aplicação com joystick para controlar robos trekking(ou carrinhos) por meio de conexão bluetooth, que são trocadas informações entre si..

Possibilidade de conectar com qualquer modulo bluetooth serial que ja esteja pareado com o aparelho.

## Instalação do ambiente de trabalho ##

Para desenvolver a aplicação, foi usado o ambiente de trabalho do eclipse usando ADT-plugin outra alternativa tem tambem a <a href="https://github.com/WickedBotz/BrinquedoIOT_Free-A">Versão AndroidStudio</a> que esta sendo continuada, ja que não existe mais suporte para o ADT-plugin para o eclipse.

<a href="http://www.programarandroid.com.br/2014/11/como-instalar-o-eclipse-ide-e.html">Link para instalação do ADT-plugin (ECLIPSE)</a>

## Instruções para importar projeto e demais dependencias##

Depois de ter instalado o ambiente e iniciado,por padrão o eclipse criou uma pasta chamada  (workspace) dentro da pasta do nome do usuario,isto seria em
 C:\Users\Administrador\workspace, ou apenas vá ao local aonde indocou para ele criar esta pasta.

(Baixando com GIT)
Dentro da pasta workspace, com o git instalado, com botao direito click em (Git bash here).
Adicione a linha de comando o codigo para clonar o repositorio (git clone https://github.com/IgorFachini/BrinquedoIOT.git).

ou

(Baixando o ZIP)
Apenas extrai o conteudo dentro da pasta workspace.

Apos isso va ate o eclipse.

1. file>import>android>Existing android code...>browse
2. Indicar a pasta (workspace)>Selecionar  BrinquedoIOT\android-support-v7-appcompat e BrinquedoIOT\Controle BT arduino.>Finish
 

Pronto, agora espere o eclipse importar e fazer build do projeto. 
O projeto principal que  interresa é o projeto Controle BT arduino, o android-support-v7-appcompat são apenas dependencias visuais e entre outros.
