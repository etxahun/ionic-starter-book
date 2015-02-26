## Comandos Básicos
https://github.com/diegonetto/generator-ionic

### Crear Proyecto
```bash
npm install -g generator-ionic
yo ionic
```


### Actualizar Proyecto
```bash
# Hacer un back up/ comitear todo antes
yo ionic
```


### Instalar Dependencias JavaScript
```bash
bower install --save
# Ejemplos
bower install --save ngCordova
bower install --save ionicons
bower install --save underscore
```


### Añadir y Borrar Un Plugin de Cordova
```bash
grunt plugin:add:<plugin>
grunt plugin:rm:<plugin>
```


### Añadir y Borrar Una Plataforma de Cordova
```bash
grunt platform:add:<platform>
grunt platform:rm:<platform>
```


### Servir la Aplicación
```bash
# Local
grunt serve
# Móvil
grunt run:<platform> --device --consolelogs
# Compilar Release
grunt build:<platform> --release
```

### Generar Icons & Splashscreen
```bash
#Son necesarias 2 imágenes png/psd/ai alojadas en el directorio resources dentro
# de la raíz del proyecto de Cordova llamadas icon y splash
# Ambas
ionic resources
# Icon
ionic resources --icon
# Splash
ionic resources --splash
```
