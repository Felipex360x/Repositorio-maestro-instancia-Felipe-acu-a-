# Repositorio-maestro-instancia-Felipe-acu-a-

en este repositorio se encuentran todo lo que este relacionado con la estancia de felipe acuña
## Microservicios y repositorios

| Servicio       | Encargado | Repositorio                                    | Puertos | 
| :------------- | :-------- | :--------------------------------------------- | :-------| 
| MS-Usuario     | Felipe    | https://github.com/Felipex360x/ms-usuario      | 8080 | 
| MS-Comprador   | Felipe      | https://github.com/Felipex360x/ms-comprador  | 8084| 
| MS-Vendedor     | Felipe     | https://github.com/Felipex360x/ms-vendedor  |  8085| 
| MS-Repartidor    | Felipe     | https://github.com/Felipex360x/ms-repartidor| 8083 | 
| MS-Vehiculo      | Felipe | https://github.com/Felipex360x/ms-vehiculo| 8082 | 
| MS-Envio      | Felipe | https://github.com/Felipex360x/ms-envios   | 8081|  

## Despliegue

Como levantar cada madulo

1) elegir la carpeta dentro de la instancia
   
 `cd entorno_desarrollo/modulo_elegido`.

2) ya dentro de la carpeta vamos a levantar el contenedor

`docker compose down`.
`docker compose up -d --build`.


#comandos para subir el repositorio

git status                              # ver qué archivos detectó

git add .                               # agregar todo lo nuevo

git commit -m "feat(auth): estructura inicial del servicio"

git push origin main

## Microservicios con sus pruebas y swagger

| Servicio       | Encargado | Swagger                                    | Test | 
| :------------- | :-------- | :--------------------------------------------- | :-------| 
| MS-Usuario     | Felipe    | ✅ Implementado      |✅ implementado   | 
| MS-Comprador   | Felipe      |⏳ Pendiente   |⏳ Pendiente | 
| MS-Vendedor     | Felipe     |✅ Implementado    | ⏳ Pendiente | 
| MS-Repartidor    | Felipe     |⏳ Pendiente  | ⏳ Pendiente  | 
| MS-Vehiculo      | Felipe |✅ Implementado  | ⏳ Pendiente  | 
| MS-Envio      | Felipe |  ⏳ Pendiente   |⏳ Pendiente  |  






