# Basic Install commands

Make sure that you update existing libraries and packages (using `sudo apt-get update`) before installation.

* Basic Installs
	* Vim (#installation/vim)
		* sudo -y apt-get install vim  vim-nox vim-gtk
  * Git
    * sudo -y apt-get install git  
* Install #installation/erlang
	* wget https://packages.erlang-solutions.com/erlang-solutions_1.0_all.deb
	* sudo dpkg -i erlang-solutions_1.0_all.deb
	* sudo apt-get update
	* sudo -y apt-get install erlang
	* 
* Rebar 3 (#installation/rebar3)
	* Install #installation/erlang
	*  git clone https://github.com/erlang/rebar3.git
	* cd rebar3
	* ./bootstrap
	* 
