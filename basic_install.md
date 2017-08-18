# Basic Install commands

Make sure that you update existing libraries and packages (using `sudo apt-get update`) before installation.

* Ubuntu Essentials
  * sudo apt install build-essential

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
