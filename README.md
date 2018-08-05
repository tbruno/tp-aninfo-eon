# EON Time Tracker

### Objetivo

Implementar la funcionalidad básica de carga de horas en forma consistente con el resto del trabajo práctico.

### Alcance

Como mínimo se debe poder:
- Para cada día ingresar la cantidad de horas que trabajo una persona en una tarea de un proyecto. Una persona puede trabajar en más de una tarea en un determinado día (incluso de diferentes proyectos)

Queda fuera del alcance:
- Autenticación y autorización: cualquier persona con acceso al sistema puede cargar
- ABM de proyectos, tareas y empleados. La registración de los mismos se puede realizar directamente en la base de datos o en memoria cuando se carga la aplicación.

## Selección de la tecnología

Cada grupo es libre de seleccionar el lenguaje y/o framework que prefiera. La cátedra provee como ejemplo básico un template basado en `Ruby on Rails` que incluye:
- Proyecto Base con integración a una Base de Datos.
- Ejecución de tests con Travis
- Integración con Cucumber para el armado de pruebas.
- Integración con Heroku.

### Desarrollo

https://guides.rubyonrails.org/getting_started.html
https://devcenter.heroku.com/articles/getting-started-with-rails5
https://blog.codeship.com/cucumber-rails-setup/