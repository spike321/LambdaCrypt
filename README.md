This is a project I did partly for class, and partly for fun and for 
learning more about gtk/glade with Haskell.


![Screenshot](http://i.imgur.com/ebuHuem.png)

This program can generate RSA public keys, and can encrypt and 
decrypt text files with them. 
Note well: This is not, nor is meant to currently be, industry
strength RSA. I might implement that in the future, or just 
make this be a front end for the existing RSA library implementation.

Installing with cabal should be straightforward. Just download the
file tree and run:
cabal configure
cabal build
cabal install

Cabal install is nessesary here, because the resources are copied
to your .cabal file during the installing, and that's where the
program tries to locate them.
