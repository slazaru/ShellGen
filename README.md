# Shell Generator 

# installation

`git clone https://github.com/slazaru/ShellGen.git`

`cd ShellGen`

`sudo ln -s $(pwd)/shellgen /usr/local/bin`

# Usage example

shellgen [attacker ip] [port to bind on] eg: `shellgen 10.10.12.14 1234`

The list of shells is getting quite long, you'll probably want to grep to filter what you want, eg for netcat shells: `shellgen 10.10.12.14 1234 | grep -i netcat -A1`

# Why fork?

Original repo was just reverse shells, I wanted to generalise the program to include bind shells as well.

# Reverse Shell fonts

http://bernardodamele.blogspot.com.br/2011/09/reverse-shells-one-liners.html

http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet
