## config.xml
Archivo principal de configuración de Cordova, aquí se indican los datos básicos de la aplicación:
* Número de Versión
* Id del Paquete
* Nombre de la Aplicación
* Descripción
* Políticas de Acceso (CORS)
* Preferencias(SplashScreen, Iconos...)

```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<widget id="com.irontec.pruebacordova" version="0.0.1" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
 <name>Prueba Cordova</name>
 <description>
       Prueba Cordova
   </description>
 <author email="info@irontec.com" href="http://irontec.com">
       Irontec SL
   </author>
 <content src="index.html"/>
 <access origin="*"/>
 <platform name="android">
    <icon src="resources/android/icon/drawable-mdpi-icon.png" density="mdpi"/>
   <splash src="resources/android/splash/drawable-land-mdpi-screen.png" density="land-mdpi"/> </platform>
 <platform name="ios">
   <icon src="resources/ios/icon/icon@2x.png" width="114" height="114"/>
   <splash src="resources/ios/splash/Default~iphone.png" width="320" height="480"/>
 </platform>
 <preference name="SplashScreen" value="screen"/>
 <preference name="SplashScreenDelay" value="5000"/>
</widget>
```

## ionic.project
Similar a config.xml pero para Ionic

```javascript
{
"name": "prueba-cordova",
"app_id": "com.irontec.pruebacordova"
}
```
