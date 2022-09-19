# El protocolo HTTP

*Hecho por Joel Barrantes*

![HTTP](/img/HTTP_0.9.png)
<br />
# INDICE.
-----------------------

### 1. Tim Berners-Lee, el creador de la web.
### 2. HTTP/0.9 – El protocolo de una sola línea
### 3. La primera comunicación
*****************************
<br />
<br />
<br />

## Tim Berners-Lee, el creador de la web

-Tim Berners-Lee introduce HTTP como una forma para que los clientes (navegadores web) se comuniquen con los servidores. 

## HTTP/0.9 – El protocolo de una sola línea

-El primer borrador, HTTP v0.9, incluye solo un método, una solicitud GET, utilizada por los clientes como una forma de solo lectura para poder ver páginas web; una petición consiste simplemente en una única linea, usando el unico método posible GET, seguido por la dirección del recurso a pedir.

```
GET /miPaginaWeb.html 
```

La respuesta también es muy sencilla: solamente consiste el archivo pedido. 

```
<HTML> Una pagina web muy sencilla </HTML>
```


-Estableció la primera comunicación entre un cliente y un servidor usando el protocolo HTTP en noviembre de 1989. 


