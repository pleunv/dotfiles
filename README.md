### Getting started


1. [Generate a new SSH key](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) by running:  
   
   ```zsh
   curl https://raw.githubusercontent.com/pleunv/dotfiles/HEAD/ssh.sh | sh -s "<your-email-address>"
   ```

2. Clone this repo to `~/.dotfiles` with:

    ```zsh
    git clone --recursive git@github.com:pleunv/dotfiles.git ~/.dotfiles
    ```

3. Run the installation with:

    ```zsh
    cd ~/.dotfiles && ./setup.sh
    ```

