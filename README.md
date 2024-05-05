# README Docker Flask Template
Éste proyecto es un contenedor de Docker, con el soporte de Python Flask para el desarrollo.

Una vez clonado el repositorio, puede construír los contenedores con:

## Crear los contenedores
$ docker compose build

## Iniciar los contenedores, con el modificador "watch", de modo que toda modificación sea incorporada en el código del Contenedor.

$ docker compose watch
[+] Running 2/2
 â Container docs-redis-1 Created                                                                                                                                                                                                        0.0s
 â Container docs-web-1    Recreated                                                                                                                                                                                                      0.1s
Attaching to redis-1, web-1
         â¦¿ watch enabled
...
