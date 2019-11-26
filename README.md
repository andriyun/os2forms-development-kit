# OS2Forms development kit
This is a [Docksal](https://docksal.io/) based development ik for OS2Forms project. 

## Requirements
Before start work with environment you need to have installed docksal
stack on you local machine. Read then manual [how to install Docksal](https://docksal.io/installation).

Get more information about docksal and how to get started with it on [official Docksal documentation](https://docs.docksal.io/).

## Get started

Before start your development process you have to clone/download this repository
to you local machine and [install Docksal](https://docksal.io/installation).

Since you have docksal installed. Run following commands to raise up development environment:
```
fin start
fin rebuild
fin si
fin init
fin symlink-os2forms
```
When you will done when all the commands you can login to drupal with `admin:admin` credentials.

You can add your changes for os2forms project inside `./os2forms` folder.

## OS2Forms commands

 * `fin init` - clones os2forms git repository to your machine
 * `fin rebuild` - build/rebuild composer-project that includes drupal core and other drupal projects for os2forms.
 * `fin si` - install drupal inside your docksal development environment
 * `fin symlink-os2forms` - creates symlink from os2forms folder for `[DRUPAL_ROOT]/modules/contrib` folder
