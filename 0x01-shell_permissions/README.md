# Shell Permissions Commands
## su [username]
The command is used to switch to different user
## whoami
Prints the effective username of current user
## groups [options] [username]
Prints the groups user is in. If username isn't specified the command prints the groups current user is in.
## chown [username] [filename]
Change file owner to username
## touch [filename]
Creates an empty file 
## chmod [options] [filename]
Edits file permissions 
 `chmod u+x hello`
The u- user. Incase we want to change group permissions use g. Everyone else use o and a for everyone else.(ugoa). The x add execute permissions while r and w add read and write permissions respectively.
Numerical notations can also be used to assign permissions 
4 - read
2 - write
1 - execute
owner, group, everyonelse.
