# Hooks de Git

### [Pyhook](https://github.com/luismayta/PyHook)

- pre-commit
- post-commit
- prepare-commit-msg
- post-receive



------------------------------------------------------

# pre-commit

- se ejecuta antes de realizar un commit

### Uso:

- Verificador de Codigo.
- Ejecucion de Test Unit

------------------------------------------------------

# post-commit

- se ejecuta despues de realizar un commit

### Uso:

- versionado a archivos static usando un archivo last_commit.
- notificaciones a usuarios email ...

------------------------------------------------------

# prepare-commit-msg

- se ejecuta antes de realizar el commit.

### Uso:

- agregar el nombre del branch al commit para gestor de proyectos como Jira, Redmine

------------------------------------------------------

# post-receive

- se ejecuta al realizar un push en el repositorio Bare.

### Uso:

- despliegues automaticos.
