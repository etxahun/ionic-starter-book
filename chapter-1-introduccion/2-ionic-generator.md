## Ionic Generator

![](http://i.imgur.com/BGrt2QK.png)  
A pesar de que el propio Ionic incluye un generador integrado, hemos decidido optar por usar un generador de Yeoman, para conservar el mismo sistema de Tareas que en otros proyectos (**Grunt**).

```bash
npm install -g generator-ionic
yo ionic
```

Este generador nos creará un proyecto base de Ionic y además nos generará un Gruntfile.js con la mayoría de las Tareas que necesitamos (listadas en la sección **Comandos Básicos**).

###Importante
*Si encontramos con que algún comando (ya sea de Ionic o de Cordova, no es ejecutable via Grunt, no tendremos más que lanzarlo con el cliente correspondiente)  
Ej: ionic resources  
**grunt resources** // Esta tarea no esta registrada ya que es una nueva funcionalidad de Ionic  
**ionic resources** // Ejecutándola con el cliente de ionic no habrá ningún problema*
