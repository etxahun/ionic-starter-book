## Inicio Básico
```bash
# Clonar el Proyecto
git clone http://git.irontec.com/repo.git /Users/iontec/workspace/cordovaDeploys/repo
git clone git@git.irontec.com/repo.git /Users/iontec/workspace/cordovaDeploys/repo
svn co http://dev.irontec.com/svn/repo /Users/iontec/workspace/cordovaDeploys/repo

# Inicializar Cordova
grunt init

# Añadir la plataforma
grunt platform:add:ios

# Lanzar la aplicación en el dispositivo
grunt run:ios --device --consolelogs

# Preparar una release
grunt build:ios --release
```
