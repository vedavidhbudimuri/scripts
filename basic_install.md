# Basic Install commands

Make sure that you update existing libraries and packages (using `sudo apt-get update`) before installation.

* Ubuntu Essentials
  * sudo apt install build-essential
  * sudo apt-get install libpq-dev python-dev libxml2-dev libxslt1-dev libldap2-dev libsasl2-dev libffi-dev
  * sudo apt -y install gcc g++ libssl-dev
  * sudo apt-get -y install libncurses5-dev libncursesw5-dev
  * sudo apt-get -y install libxml2-utils
  * sudo apt install python-minimal
  * export LC_ALL="en_US.UTF-8"
  * export LC_CTYPE="en_US.UTF-8"
  * sudo dpkg-reconfigure locales
  * sudo apt -y install libkrb5-dev
  * sudo apt-get -y install libwxbase3.1-0-unofficial libwxbase3.1-devlibwxgtk3.1-0-unofficial libwxgtk3.1-dev wx3.1-headers wx-common libwxgtk-webview3.1-0-unofficial libwxgtk-webview3.1-dev libwxgtk-media3.1-0-unofficial libwxgtk-media3.1-dev libwxbase3.1-0-unofficial-dbg libwxgtk3.1-0-unofficial-dbg libwxgtk-webview3.1-0-unofficial-dbg libwxgtk-media3.1-0-unofficial-dbg wx3.1-i18n wx3.1-examples

sudo apt install docker.io
sudo gpasswd -a $USER docker

* Basic Installs (#installatino/basic_installs)
	* Compiler (#installatino/basic_installs/compiler)
    	* sudo apt install gcc g++
	* Vim (#installatino/basic_installs/vim)
    	* sudo apt -y install vim  vim-nox vim-gtk
	* Git (#installatino/basic_installs/git)
    	* sudo apt -y install git 
  	* wget (#installation/basic_installs/wget)
    	* sudo apt -y install wget  
  	* java (#/installation/basic_installs/java)
    	* sudo apt-get install default-jre
    	* sudo apt-get install default-jdk
  

* Install #installation/erlang
  	* Install gcc #installation/basic_installs/compiler
	* Install java #installation/basic_installs/java
    * sudo apt-get install build-essential libncurses5-dev openssl libssl-dev
	* wget http://packages.erlang-solutions.com/site/esl/esl-erlang/FLAVOUR_1_general/esl-erlang_18.0-1~ubuntu~precise_amd64.deb
	* sudo dpkg -i esl-erlang_18.0-1~ubuntu~precise_amd64.deb
	* sudo apt-get update
	* sudo apt-get -y install erlang

* Rebar 3 (#installation/rebar3)
	* Install #installation/erlang
	* git clone https://github.com/erlang/rebar3.git
	* cd rebar3
	* ./bootstrap
