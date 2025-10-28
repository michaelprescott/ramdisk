Dependencies:

Optional Dependencies:
    ShellCheck - A shell script static analysis tool
        https://github.com/koalaman/shellcheck

    shfmt - Autoformat shell script source code
        brew install shfmt
    
    altshfmt - an experimental tool for formatting AltSH (alternative shell script) with extended syntax that cannot be formatted correctly by shfmt. This is implemented as a wrapper for shfmt
        pushd $HOME/Developer/Tools
        git clone https://github.com/shellspec/altshfmt.git
        popd

    shell-format - VSCode extension - A formatter for shell scripts, Dockerfile, gitignore, dotenv, /etc/hosts, jvmoptions, and other file types
        https://marketplace.visualstudio.com/items?itemName=foxundermoon.shell-format
        Install the shell-format extension and change shellformat.path in settings.json to the path to the altshfmt (or altshfmt.bat for windows).
        Downgrade to 7.2.5 because the latest, 7.2.8, is failing