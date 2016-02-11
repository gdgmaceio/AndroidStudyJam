# Android study Jams
E aew!

Esse documento é pra você que vai levar seu notebook para o Android Study Jams.
Você vai precisar instalar alguns programas que ajudam a criar apps para Android, e para poder rodar o app no seu celular(se ele for android é claro).
Todos os instaladores estarão divididos entre as plataformas *Windows*, *Linux* e *Mac*.

Então vamos lá, primeiro vamos instalar o JDK.

## Instalando o JDK
O JDK é uma ferramenta básica para desenvolvimento com Java.

* [Windows x86](http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-windows-i586.exe)
* [Windows x64](http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-windows-x64.exe)
* [Linux x86](http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-linux-i586.tar.gz)
* [Linux x64](http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-linux-x64.tar.gz)
* [Mac x64](http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-macosx-x64.dmg)

Para os usuários de Linux também é possível usar o seguinte [script](https://raw.githubusercontent.com/Padawan-org/Install-Scripts/master/java.sh).

## Instalando o Android SDK
Agora que já instalamos o JDK precisamos instalar as ferramentas específicas para desenvolvimento de Apps Android.

* [Windows](http://dl.google.com/android/installer_r24.4.1-windows.exe)
* [Linux](http://dl.google.com/android/android-sdk_r24.4.1-linux.tgz)
* [Mac](http://dl.google.com/android/android-sdk_r24.4.1-macosx.zip)

### Linux 64 bits
Se você usa um Linux 64 bits, você vai precisar habilitar a plataforma 32-bits para rodar alguns programas do SDK.

		sudo dpkg --add-architecture i386
		sudo apt-get update

Para o Ubuntu 13.10 e versões superiores.

		sudo apt-get install libncurses5:i386 libstdc++6:i386 zlib1g:i386

Versões anteriores rode

		sudo apt-get install ia32-libs

## Emulador
O Android SDk vem com um emulador, mas ainda é muito lento, então vamos instalar outro emulador, o GennMotion.
A instalação do emulador é *opcional*, você pode usar o emulador padrão ou o seu *próprio dispositivo*.

O GenyMotion usa o *VirtualBox* para criar os dispositivos virtuais. Mas no *Linux* e no *Mac* é necessário instalar o *virtualBox* separadamente, então vamos começar com a instalação do *VirtualBox*.
* [Linux](https://www.virtualbox.org/wiki/Linux_Downloads)
* [Mac](http://download.virtualbox.org/virtualbox/5.0.14/VirtualBox-5.0.14-105127-OSX.dmg)
Cada versão do Linux, tem um instalador próprio, então o link lhe envriará para página com a lista.

* [Windows](http://files2.genymotion.com/genymotion/genymotion-2.6.0/genymotion-2.6.0-vbox.exe)
Ubuntu 14.04 e versões anteriores ou o Debian 8
* [Linux X86](http://files2.genymotion.com/genymotion/genymotion-2.6.0/genymotion-2.6.0-linux_x86.bin)
* [Linux x64](http://files2.genymotion.com/genymotion/genymotion-2.6.0/genymotion-2.6.0-linux_x64.bin)
Ubuntu 15.04 e versões mais novas.
* [Linux x64](http://files2.genymotion.com/genymotion/genymotion-2.6.0/genymotion-2.6.0-ubuntu15_x64.bin)

O GennyMotion precisa de um cadastro, o recomendado você faça [cadastro](https://www.genymotion.com/account/create/) no site.

## Drivers
No windows é necessário instalar drivers para fazer a comunicação com um dispositivo real, se você pretende usar seu aparelho e usa windows acesse [essa página](http://developer.android.com/intl/pt-br/tools/extras/oem-usb.html) e clink no link do fabricante do seu aparelho.
Se seu aparelho é um Nexus, siga [esse link](http://developer.android.com/intl/pt-br/sdk/win-usb.html).

