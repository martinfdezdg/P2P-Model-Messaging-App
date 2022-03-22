# White-phone

#### Aplicación de intercambio de fotos entre nodos distribuidos

Se trata de un híbrido entre arquitectura cliente-servidor y peer-to-peer en la que el intercambio de información se realiza directamente entre los propios clientes, y el servidor únicamente actúa proporcionando datos de qué hay disponible en el sistema y quiénes son los nodos propietarios.

## Procedimiento de compilación
> Abrir terminal en el directorio actual

Compilación:
```shell
javac src/Cliente/*.java src/Servidor/*.java src/Mensaje/*.java src/Interfaz/*.java src/Utilidades/*.java
```

## Procedimiento de ejecución
> Abrir terminal en el directorio actual

Ejecución del cliente:
```shell
java src/Cliente/MainCliente.java ip_cliente ip_servidor puerto_servidor
```

Ejecución del servidor:
```shell
java src/Servidor/MainServidor.java ip_servidor puerto_servidor
```
