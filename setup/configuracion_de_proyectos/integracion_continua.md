# Integración Continua

Con CI (ya sea Circle CI o Travis) podemos revisar que los tests de cada proyecto pasen, recibiendo feedback en nuestros commits y PRs antes de mergear. Además, en varios proyectos, con CI hacemos deploy automáticamente tras mergear a master.

## Circle CI (Repositorios privados)

[[https://circleci.com/add-projects/gh/platanus](https://circleci.com/add-projects/gh/platanus)]: Una vez logueado, buscar repositorio y presionar `Follow Project`.

Por defecto Circle CI intenta adivinar qué es necesario para correr los tests pero hay excepciones para las cuales es necesario agregar un archivo de configuración `circle.yml`:

### Variables de Entorno

Para realizar deploy en ciertos ambientes hay que agregar información a las variables de entorno, como nombres de usuario o API keys.

1. Buscar ⚙️ en el proyecto seleccionado.

1. Seleccionar `Environment Variables`

1. Seleccionar `Add Variable`

### Potassium

Con Potassium cualquier proyecto Rails que use la receta `heroku` va a traer el archivo que necesita CircleCI para hacer su trabajo.
