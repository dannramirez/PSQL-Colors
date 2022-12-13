# PSQL-Colors
This if for .psqlrc config all you need to do is appent or replace from .psqlrc file and append to .zshrc or .bashrc config file

- %M refers to the database server’s hostname – is “[local]” if the connection is over a Unix domain socket
- %> refers to the listening port
- %n refers to the session username
- %/ refers the current database
- %R refers to whether you’re in single-line mode (^) or disconnected (!) but is normally =
- %# refers to whether you’re a superuser (#) or a regular user (>)
- %x refers to the transaction status – usually blank unless in a transaction block (*)

There are various colors you can use – change the value 31 to:

- 32 for green
- 33 for yellow
- 34 for blue
- 35 for magenta
- 36 for cyan
- 37 for white

![View of psql with colors](/Final.png "psql promt")
