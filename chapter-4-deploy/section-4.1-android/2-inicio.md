## Inicio Básico
```bash
# Clonar el Proyecto
git clone http://git.irontec.com/repo.git /Users/iontec/workspace/cordovaDeploys/repo
git clone git@git.irontec.com/repo.git /Users/iontec/workspace/cordovaDeploys/repo
svn co http://dev.irontec.com/svn/repo /Users/iontec/workspace/cordovaDeploys/repo

# Inicializar Cordova
grunt init

# Añadir la plataforma
grunt platform:add:android

# Lanzar la aplicación en el dispositivo
grunt run:android --device --consolelogs

# Es posible que no pille los plugins por defecto, si es así, desinstalarlos e instalarlos de nuevo
grunt plugin:rm:<plugin>
grunt plugin:add:<plugin>


# Preparar una release
grunt build:android --release
```
