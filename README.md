# Qué es Laravel?

Es un framework para PHP, se pueden desarrollar sistemas de login/ CRUD, BD. 

## Requisitos para instalar Laravel

- Tener instalados PHP, Node y Composer
  - Para instalar PHP, instalé directamente Xampp que ya trae la version actualizada de PHP. 
  - Links de instalación: 
    - https://www.apachefriends.org/es/download.html (xampp)
    - https://nodejs.org/es (Node)
    - https://getcomposer.org/download/ (Composer)

Se puede verificar la instalación de la siguente manera:
![image](image.png)

Además, verificar que existan las variables de entorno para cada programa instalado:

![image1](image-1.png)

Composer sirve para administrar la dependencias de laravel. (como npm)
- Tener el instalador de Laravel (para obtenerlo: `composer global require laravel/installer`)

php artisan --version para chequear la version de laravel
que es artisan? la interfaz de linea de comandos de laravel

`laravel new propiedades-app`
para ejecutar la app : `php artisan serve`