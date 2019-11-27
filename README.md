# tailcolor

tail -f that can now make colorful lines using the words provided in the script

# Installation

bash users:

`cd /usr/bin && sudo git clone https://github.com/f0s3/tailcolor && cd tailcolor && echo "export PATH=\$PATH:$(pwd)" >> ~/.bashrc && sudo chmod +x tailcolor`

zsh users:

`cd /usr/bin && sudo git clone https://github.com/f0s3/tailcolor && cd tailcolor && echo "export PATH=\$PATH:$(pwd)" >> ~/.zshrc && sudo chmod +x tailcolor`

IMPORTANT: Restart your bash or zsh for changes to apply, or run:

bash users:

`source ~/.bashrc`

zsh users:

`source ~/.zshrc`

It will start a bash/zsh session using new config file with tailcolor in the path, so `exit`ing the terminal will exit only the session, created by the above commands (`source ~/.bashrc` or `source ~/.zshrc`), so you will need to exit twice when done working with current terminal window.

My suggestion is to simply close the terminal tab in which the installation happened and open the new one instead of the previously closed one.

# Usage

`tailcolor path/to/file black="black" white="white" yellow="yellow" cyan="cyan" magenta="magenta" red="red" green="green" blue="blue"`

You can put regexes in any colors' value, like cyan="\sINFO".
