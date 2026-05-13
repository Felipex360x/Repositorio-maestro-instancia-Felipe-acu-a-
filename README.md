# Repositorio-maestro-instancia-Felipe-acu-a-

en este repositorio se encuentran todo lo que este relacionado con la estancia de felipe acuña
## Microservicios y repositorios

| Servicio       | Encargado | Repositorio                                    | Puertos | 
| :------------- | :-------- | :--------------------------------------------- | :-------| 
| MS-Usuario     | Felipe    | https://github.com/Felipex360x/ms-usuario      | 8080 | 
| MS-Comprador   | Felipe      | https://github.com/Felipex360x/ms-comprador  | 8084| 
| MS-Vendedor     | Felipe     | en espera   |  8085| 
| MS-Repartidor    | Felipe     | https://github.com/Felipex360x/ms-repartidor| 8083 | 
| MS-Vehiculo      | Felipe | https://github.com/Felipex360x/ms-vehiculo| 8082 | 
| MS-Envio      | Felipe | en espera   | 8081|  

## Despliegue

Cada integrante levanta su servicio en su propia EC2 con

`docker compose up -d`.

#comandos para subir el repositorio
git status                              # ver qué archivos detectó

git add .                               # agregar todo lo nuevo

git commit -m "feat(auth): estructura inicial del servicio"

git push origin main
