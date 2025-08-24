# helldiver README

Take out those Terminades bugs and automoton errors from your code with this Patriotic Theme.
dive Dive DIVE!!!

To build your own Theme see this documentation:

https://code.visualstudio.com/api/references/



brew install node
npm install -g yo generator-code
yo code

vsce package
code --install-extension ./helldiver-0.X.X.vsix

command like to make iterm look better:
autoload -U colors && colors\nexport PS1="%{$fg_bold[yellow]%}%n@%m %{$fg_bold[green]%}%~ %{$reset_color%}$ "\n
