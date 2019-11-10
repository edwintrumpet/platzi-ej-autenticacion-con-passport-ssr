## Server side render de prueba

Server side render de prueba usado en el curso de autenticación con Passport de la Escuela de Javascript

## Instalación

```shell
npm i
```

## Scripts

- `npm run dev`  
Corre la aplicación en modo desarrollo
- `npm start`  
Corre la aplicación en modo producción

## Notas

### Creación de proyecto en Google api para hacer autenticación en OAuth2.0

1. Vamos a la [Consola de APIs  y servicios](https://console.developers.google.com) de Google
2. Creamos un proyecto
3. En el menú lateral izquierdo seleccionamos **Pantalla de consentimiento** y en **Nombre de la aplicación** asignamos un nombre que en este caso será **Platzi videos**
4. En el menú lateral izquierdo seleccionamos **Credendials > Create credentials > OAuth client ID**
5. Nos aseguramos de elegir **Web application** como tipo de aplicación
6. Luego establecemos el nombre del cliente que en nuestro caso será **SSR server**, el **Authorized JavaScript Origins:** _http://localhost:8000_ y el **Authorized redirect URIs:** _http://localhost:8000/auth/google-oauth/callback_, después se cambiarán los valores en producción.
7. Al final copiamos **Client ID** y **Client secret** y los usamos en nuestro entorno como **GOOGLE_CLIENT_ID** y **GOOGLE_CLIENT_SECRET**
