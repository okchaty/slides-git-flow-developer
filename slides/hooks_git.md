# Hooks de Git

- pre-commit
- post-commit
- prepare-commit-msg
- post-receive



------------------------------------------------------

# [pre-commit](http://pre-commit.com/)

- se ejecuta antes de realizar un commit


### Uso:

- Verificador de Codigo.
- Ejecucion de Test Unit

------------------------------------------------------

# post-commit

- se ejecuta despues de realizar un commit

### Uso:

- Versionado de archivos static empleando last_commit.
- Notificaciones a usuarios email, etc.

------------------------------------------------------

# prepare-commit-msg

- se ejecuta antes de realizar el commit.

### Uso:

- agregar el nombre del branch hacia el titulo del commit

------------------------------------------------------

# post-receive

- se ejecuta al realizar un push en el repositorio Bare.

### Uso:

- despliegues automaticos.
