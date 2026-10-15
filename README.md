# git-config
My personal git configuration

To use, create symlinks for `.gitconfig` and `.gitignore_global` in your home directory:

    # Assuming path to git-config is `~/Git/git-config`
    ln -s Git/git-config/.gitconfig ~/.gitconfig
    ln -s Git/git-config/.gitignore_global ~/.gitignore_global

There is also a script for setting the command line prompt:

    # Assuming your bash profile loads everything in `~/.bash_profile.d/`
    ln -s Git/git-config/git-prompt ~/.bash_profile.d/git-prompt
