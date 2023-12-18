### Despliegue en Heroku
- **Crea una aplicación en Heroku:** Desde tu terminal, navega hasta el directorio de tu proyecto y ejecuta ```heroku create nombre-de-tu-aplicacion``` para crear una nueva aplicación en Heroku.
- **Asocia el repositorio de Git:** Si aún no lo has hecho, inicializa un repositorio git en tu proyecto con ```git init```. Luego, agrega el control remoto de Heroku con ```heroku git:remote -a nombre-de-tu-aplicacion```.
- **Realiza el despliegue:** Haz commit de tus cambios con ```git add .``` y ```git commit -m "Mensaje descriptivo"```. Luego, despliega tu aplicación en Heroku con ```git push heroku main.```


### Configurar mongo_uri:
- **crear o actualizar:** ```heroku config:set MONGO_URI="mongodb+srv://miusuario:mipassword@mycluster/" --app nombre-de-tu-app-en-heroku```
- **eliminar:** ```heroku config:unset MONGO_URI --app nombre-de-tu-app-en-heroku```

### Consultar las variables de entorno
Puedes consultar las variables de entorno y configuraciones que has establecido en tu aplicación de Heroku usando el comando 
- ```heroku config --app nombre-de-tu-app-en-heroku```


  
