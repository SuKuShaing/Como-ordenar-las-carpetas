van a estar todos los archivos de mi proyectos
Conexiones a la base de datos
las rutas
los servicios
los testing
los modelos
los controladores
los middlewares
paquetes de archivos utilitarios


para que las carpetas funcionen como un paquete de python,
las carpetas deben contener un archivo __init__.py
este archivo puede estar vacío o contener código
este archivo se ejecuta cuando se importa el paquete
por lo que se puede usar para inicializar el paquete
o para importar módulos del paquete
por ejemplo, si se tiene un paquete con la siguiente estructura
```
package/
    __init__.py
    module.py
```
se puede importar el módulo module.py desde el archivo __init__.py
```
from .module import *
```
de esta forma, al importar el paquete, se importa también el módulo
esto es útil para importar módulos que se usan frecuentemente
o para inicializar el paquete