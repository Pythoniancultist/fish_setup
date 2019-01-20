###Commands to Improve Usability of Fish Shell
To make Fish display full path to your current location, add following line to your fish config file;

* set -U fish_prompt_pwd_dir_length 0
***
To make Fish activate Anaconda environments; 

* conda info --root

Add following line to your fish config file.

*  source /**YOUR_INSTALL_DIR**/etc/fish/conf.d/conda.fish

***
To disable the annoying Fish greeting message, add the following line to your Fish config file;

* set fish_greeting

Tip: Anything you write after 'fish_greeting' will be your new greeting message. 

***
To make Fish your default shell;

* chsh -s /usr/bin/fish

Then, restart.



