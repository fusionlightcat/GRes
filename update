#!/bin/bash
git pull origin master
rm -r assets/
unzip -o GRpack.zip
rm readme.txt
echo 'GRpack Ressources. Use with the GR Project only' > readme.txt
git add --all
git commit -m '$1'
git push origin master
