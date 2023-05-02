
# Proyecto Firebase Cloud Messenging

Este proyecto es una aplicación Android simple que utiliza Firebase Cloud Messaging (FCM) para recibir notificaciones push. Está desarrollado en Kotlin utilizando Android Studio.

## Requisitos

- Android Studio
- Cuenta de Firebase y configuración de Firebase Cloud Messaging

## Instalación

1. Clona este repositorio o descarga el código fuente.

_bash_
```
git clone https://github.com/LeJammes454/ProyectoFirebaseCloudMessenging.git
```

2.  Abre Android Studio e importa el proyecto desde la carpeta clonada o descargada.
    
3.  Asegúrate de haber configurado Firebase Cloud Messaging en tu aplicación siguiendo las instrucciones en la [documentación oficial](https://firebase.google.com/docs/cloud-messaging/android/client).
    
4.  Compila y ejecuta la aplicación en un dispositivo o emulador Android.
    

## Uso

1.  Al abrir la aplicación, se mostrará el token FCM del dispositivo en un Toast y en el Logcat.
    
2.  Utiliza un servidor o una herramienta para enviar notificaciones push a este dispositivo utilizando el token FCM. Puedes probar el servidor Node.js creado en el repositorio relacionado: [Push Notification Sender](https://github.com/LeJammes454/ProyectoFCMServidor.git).
    
3.  Cuando la aplicación recibe una notificación push, se mostrará en la barra de estado del dispositivo.
    

## Licencia

Este proyecto está bajo la licencia MIT.

🐱‍💻
