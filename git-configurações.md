# habilita edição do git pelo vscode
git config --global core.editor code

# abre as configurações do git no vs code 
git config --global --edit



# template base
[user]
	email = marcosaureliofarias2023@gmail.com
	name = marcos
[core]
	editor = code --wait
[alias]
	s = !git status -s
	c = !git add --all && git commit -m
	l = !git log --pretty=format:'%C(blue)%h %C(red)%d C(white)%s - %C(cyan)%cn, %C(green)%cr'