# Configuracion de entorno

Esta es la configuracion que uso para mi entorno de programacion en win10 usando gitbush.

## Perzonalizacion con oh-my-posh

Instrucciones sobre cómo instalar oh-my-posh: https://ohmyposh.dev/docs/installation/windows

Crear .bashrc si no esta creado

Dentro del .bashrc poner: eval "$(oh-my-posh init bash)"

Ejecutamos el .bashrc: exec bash

Descargar e instalar hack nerd font en: https://www.nerdfonts.com/ 

### Customize
En .bashrc:
eval "$(oh-my-posh init bash --config ~/AppData/Local/Programs/oh-my-posh/themes/jandedobbeleer.omp.json)"

para cambiar el tema desde pa pagina: https://ohmyposh.dev/docs/themes

## Configuracion mysql
Esto para poder ejecutar comando mysql desde bash
cd ~ && echo "alias mysql=\"winpty mysql\"" >> .bash_profile

## Congifuracion de neovim y treeview (...proximamente)



## Créditos

Lista de los autores o contribuyentes del proyecto.
https://www.youtube.com/watch?v=Bkaox81ppds&ab_channel=gr4bit
https://stackoverflow.com/questions/32620670/git-bash-mysql-blank
