# Configurations

Just some configurations for my dev tools on Mac OSX and Ubuntu.

# Usage

First ensure you have python3 and pip3.

`sudo apt-get install python-pip3 && sudo apt-get install python3.6`

Then pip3 install everything from the requirements.

`pip3 install -r pip_requirements.txt`

Next move the .tmux.conf file to ~/

`cp ./.tmux.conf ~/ && source ~/.tmux.conf`

To get samba working for file transfer, ensure it's installed:

`sudo apt-get install samba && sudo smbpasswd -a sujeethjinesh`

Move smb.conf to /etc/samba/smb.conf and restart

`sudo cp ./smb.conf /etc/samba/smb.conf && sudo /etc/init.d/smbd restart`


