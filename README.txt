Versão do XFCE4 : 4.12

Esse pacote contem todos os últimos códigos fontes do site oficial : http://archive.xfce.org/
Inclue também aplicativos para deixar um Desktop completo
- xarchiver
- mousepad
- ristretto
- thunar plugins
- xfce4 plugins
- pulseaudio

Apenas lembrando que não adicionei nenhum pacote especial devido ao pulseaudio, eu apenas inclui o pulseaudio no próprio xfce4-mixer

Requerimentos:

Primeiro você precisa saber se você está dentro das dependências mínimas
- Slackware64 Current
- Pacote de Áudio instalado (Pulse ou Jack)

Como instalar?
*Pulse* Descompacte o arquivo com o comando "tar xvf xfce-install.tar.xz"
*Pulse* Entre na pasta "install" que acabou de ser criada
*Pulse* Então execute o script com o comando "sudo sh xfce-install.sh"

*Jack* Descompacte o arquivo com o comando "tar xvf xfce-install-jack.tar.xz"
*Jack* Entre na pasta "install-jack" que acabou de ser criada
*Jack* Então execute o script com o comando "sudo sh xfce-install-jack.sh"

Como compilar?
Descompacte o arquivo com o comando "tar xvf xfce-source.tar.xz"
Entre na pasta "source" que acabou de ser criada

*Pulse* Então execute o script com o comando "sudo sh build-xfce.sh"
*Jack* Então execute o script com o comando "sudo sh build-xfce-jack.sh"

-----------------------------------------------

XFCE4 version: 4:12

This package contains all the latest source code from the official site: http://archive.xfce.org/
Also includes applications to make a complete Desktop
- Xarchiver
- Mouse pad
- Ristretto
- Thunar plugins
- Xfce4 plugins
- Pulseaudio

Just remembering that did not add any special package due to pulseaudio, I just pulseaudio includes the xfce4-mixer itself

Requirements:

First you need to know if you are within the minimal dependencies
- Current Slackware64
- Audio Pack installed (Pulse or Jack)

How to install?
*Pulse* Unzip the file with the command "tar xvf xfce-install.tar.xz"
*Pulse* Enter the "install" folder you just created
*Pulse* Then run the script with the command "sudo sh xfce-install.sh"

*Jack* Unzip the file with the command "tar xvf xfce-install-jack.tar.xz"
*Jack* Enter the "install-jack" folder you just created
*Jack* Then run the script with the command "sudo sh xfce-install-jack.sh"

How to build?
Unzip the file with the command "tar xvf xfce-source.tar.xz"
Enter the "source" folder you just created

*Pulse* Then run the script with the command "sudo sh build-xfce.sh"
*Jack* Then run the script with the command "sudo sh build-xfce-jack.sh"

-------------------------------------------------

Changelogs : 13/07/2015

- adicionado cursor para x11 dmz-white
- xfce4-taskmanager compilado em GTK3
- xfce4-panel compilado em GTK3
- mousepad compilado em GTK3
- existe apenas mais um app do xfce4 que pode ser compilado em GTK3 que é o xarchiver, porém não consegui, portanto continua em GTK2
- atualizado todos SlackBuilds pois estavam tentando copiar documentação do source que não existia ou faltava documentação a ser copiada

Changelogs : 20/07/2015

- adicionado opção para compilar em Jack Audio
