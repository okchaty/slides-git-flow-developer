# Git Flow

- es un flujo de trabajo para la práctica de Desarrollo propuesto por Vicente Driessen

### [nvie/gitflow](https://github.com/nvie/gitflow)
### [Image Git Flow](https://jacovanstaden.files.wordpress.com/2011/03/git-flow-overview.jpg)

------------------------------------------------------

# Vincent Driessen

Ingeniero de Software Interesado en el desarrollo de Web y Herramientas de Programacion y Tecnologias (Python, Vim y Git)

- [Web](http://nvie.com/about)
- [@nvie](https://twitter.com/nvie)
- [github.com/nvie](https://github.com/nvie)


------------------------------------------------------
# Install

## *Linux*

### Debian

- apt-get install git-flow

### Centos

- yum install git-flow


------------------------------------------------------

# Install OS X And Windows

### *OS X*

- brew install git-flow

### Windows

- [Install](https://github.com/nvie/gitflow/wiki/Windows)

------------------------------------------------------

# Init

    !bash
    git flow init


## Especificar las ramas a trabajar

- Branch name for production releases
- Branch name for "next release" development

------------------------------------------------------

# Feature

- Ramas creadas para hacer nuevos desarrollos.

### Ejemplos:

- Casos de Uso.
- Tareas.
- Historias de Usuario.
- Card.

## Commands

    !bash
    git flow feature list
    git flow feature start
    git flow feature finish
    git flow feature pull
    git flow feature publish

------------------------------------------------------

# Release

- Un Entregable, Finalizado de un sprint.

### Ejemplos:

- Final de un Sprint.
- Presentacion de un Avance de Funcionalidad.

## Commands

    !bash
    git flow release list
    git flow release start
    git flow release publish
    git flow release pull
    git flow release finish

------------------------------------------------------

# Hotfix

- son caracteristicas no deseadas que se tienen que Corregir inmediatamente.

### Ejemplos:

- Bugs en Production.

## Commands

    !bash
    git flow hotfix start
    git flow hotfix finish

------------------------------------------------------

# Support

- Aun no lo entiendo correctamente.

## Commands

    !bash
    git flow support start
    git flow support finish
