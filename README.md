# DataWareHouse
**Proyecto Final Data Warehouse**

Sistema para la administracion de contactos de clientes para una compañia.

#Modo Freelance

##Entregables
- Carpeta FrontEnd
- Carpeta BackEnd


## Requisitos

### Instalar NodeJS
  - [Descargar Nodejs](https://nodejs.org/en/download/)

### Instalar XAMPP
  - [Descargar XAMPP](https://www.apachefriends.org/es/download.html)

### Instalar MySQL Workbench (*opcional)
  - [Descargar Postman](https://www.postman.com/product/api-client/)

### Instalar Postman
  - [Descargar Postman](https://www.postman.com/product/api-client/)

## Despliegue

## BackEnd
**1) Preparacion de archivos**

* Clonar el repositorio desde github accediendo al link: https://github.com/120m4n/AcamicaDatawarehouse.git

**2)Descomprimir los archivos y ubicar una terminar en la carpeta Backend

**3) Instalar dependencias**
```
npm install
```

**3) Migracion de esquema de base de datos**
* Iniciar los modulos MYSQL y Apache desde el panel de XAMPP.
![Alt panel xampp](./Migracion/Panel_XAMPP.PNG?raw=true "Panel XAMPP")
* Abrir XAMPP e iniciar los servicios de **Apache Web Server** y **MySQL Database**
* Abir el navegador a la(http://localhost/phpmyadmin/)**.
* En la pestaña Importar, boton "Seleccionar archivo" buscar la ruta local al archivo "Creacion_Schema.sql". 
El archivo se encuenta en la ruta: **./Migracion/Creacion_Schema.sql**
* Ejecutar la importacion con el boton "Continuar"
![Alt importacion data](./Migracion/Importacion.PNG?raw=true "importacion data")
**Opcional
Ejecutar el archivo "Creacion_Schema.sql" en MySQL Workbench.

* Modelo Entidad-Relacion.
![Alt modelo ER](./Migracion/ER_Diagram.PNG?raw=true "Modelo ER")

**4) Generar el modelo de prisma
```
npx prisma generate
```

**5) Iniciar el servidor**

node ./src/app.js

## FrontEnd

**1) Inicializar index.html**

## CREDENCIALES PARA PRUEBA
# ADMIN
{
    "username":"adminstrador",
    "password":"adminstrador"
}

# USER
{
    "username":"usuario",
    "password":"usuario"
}


