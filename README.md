# White-phone
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
