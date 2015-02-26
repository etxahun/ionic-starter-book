## Añadiendo la Key Store a un proyecto
Para añadir la keystore a nuestro proyecto es necesario modificar el fichero platforms/android/ant.properties y añadir las siguientes líneas
```ini
key.store=/home/user/Documentos/keystores/firma.keystore
key.alias=alias
key.store.password=storepass
key.alias.password=aliaspass
```
