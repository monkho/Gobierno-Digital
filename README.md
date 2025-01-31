## Participante
Obed Gonzalez Hernandez

## Despliegue
Para desplegar este proyecto, debes clonar este repositorio:
``` bash
git clone https://github.com/monkho/Gobierno-Digital.git
```
Una vez clonado, navega dentro de la carpeta y ejecuta el comando: 
``` bash
composer run build
```
Este comando inicializa el proyecto e instala sus dependencias, ademas de las respectivas migraciones de la base de datos, una vez terminado este proceso ejecuta el siguiente comando:
``` bash
composer run dev
```
> [!NOTE]
> Cabe aclarar que es necesario tener instalado **composer**, **laravel**, **artisan**, **xampp** (para MySQL) y **Postman** para hacer las consultas.

Lo que va a iniciar un servidor en `localhost:8000` 
## Observaciones generales
Considero que la propuesta de base de datos contiene una tabla innecesaria, pues la relación entre las tablas `user` y `role` es una relación M-1, es decir, que la tabla `user` debe contener la llave foránea para el rol que se desee asignar. \
Estoy consciente que aún me falta mucho camino por recorrer, y con un poco más de background dentro de Laravel, pude haber realizado de la mejor manera esta prueba.