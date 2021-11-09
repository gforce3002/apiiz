# apiiz

Construccion de un login con JWT

Primero debemos ingresar el paquete de jwt para laravel con el siguiente comando

composer require tymon/jwt-auth


ahora vamos a la carpeta config y buscarmos el archivo app.php, buscamos la seccion

/*
* Application Service Providers...
*/

y agregar al final del grupo de instrucciones esta linea

Tymon\JWTAuth\Providers\LaravelServiceProvider::class,