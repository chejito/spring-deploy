## Despliegue de app Spring Boot en Heroku

Crear archivo ` system.properties` en el proyecto con el contenido:

```
java.runtime.version=17
```

1. Crear cuenta en heroku.com y github.com 
2. Tener configurado git en el pc:
   1. `git config --global user.name "chejito"`
   2. `git config --global user.email smndz81@gmail.com`
3. Subir el proyecto a GitHub desde Intellij IDEA desde la opción: VCS > Share project on GitHub
4. Desde heroku crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el deploy