# ion-login-firebase


#### Paso número 1
Descarga o clona el proyecto
#### Paso número 2
Abrir una terminal dentro de la carpeta y ejecutar  el comando
```
npm install
```
#### Paso número 3
Dentro del proyecto en los en el archivo src/enviroments/enviroment.ts y src/enviroments/enviroment.prod.ts intercambia los valores de la variable firebaseConfig por los de tu proyecto de firebase
```javascript
export const firebaseConfig = {
  apiKey: '<your-api-key>',
  authDomain: '<your-project-authdomain>',
  databaseURL: '<your-database-URL>',
  projectId: '<your-project-id>',
  storageBucket: '<your-storage-bucket>',
  messagingSenderId: '<your-messaging-sender-id>',
  appId: "<your-app-id>",
};
```

# Listo para el despliegue, ahora ya sabes que hacer...
 psst... psst..  (ionic serve)
