# tailcolor

tail -f that can now make colorful lines using the words provided in the script

# Installation

bash users:

`cd /usr/bin && git clone https://github.com/f0s3/tailcolor && cd tailcolor && echo "export PATH=\$PATH:$(pwd)" >> ~/.bashrc`

zsh users:

`cd /usr/bin && git clone https://github.com/f0s3/tailcolor && cd tailcolor && echo "export PATH=\$PATH:$(pwd)" >> ~/.zshrc`

IMPORTANT: Restart your bash or zsh for changes to apply, or run:

bash users:

`source ~/.bashrc`

zsh users:

`source ~/.zshrc`

It will start a bash/zsh session using new config file with tailcolor in the path, so `exit`ing the terminal will exit only the session, created by the above commands (`source ~/.bashrc` or `source ~/.zshrc`), so you will need to exit twice when done working with current terminal window.

My suggestion is to simply close the terminal tab in which the installation happened and open the new one instead of the previously closed one.

# Usage

`tailcolor path/to/file`

# Changing the keywords

If you want to change the words on which the color is applied, edit the script.

NOTE: This documentation's section is in process of writing so I will update it as soon as I implement some of the functionality needed to change the keywords on-the-fly.
