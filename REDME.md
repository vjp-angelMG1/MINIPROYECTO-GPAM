# MINI PROYECTO DWEC : Análisis de YouTube

## 1. Introducción

En este proyecto vamos a analizar el funcionamiento de una aplicación web real: **YouTube**.

YouTube es una plataforma de vídeo que permite a los usuarios buscar, reproducir y compartir vídeos. Para funcionar utiliza una arquitectura cliente-servidor, en la que una parte de la aplicación se ejecuta en el navegador del usuario y otra parte se ejecuta en los servidores de YouTube.

El objetivo de este proyecto es analizar qué parte corresponde al frontend, qué parte corresponde al backend y cómo se comunican mediante peticiones HTTP/HTTPS.

---

## 2. Aplicación elegida

**Aplicación:** YouTube

**Página web:** https://www.youtube.com/

La acción que vamos a analizar es la siguiente:

1. El usuario entra en YouTube.
2. Escribe una búsqueda en el buscador.
3. YouTube envía peticiones al servidor.
4. El servidor procesa la petición.
5. El navegador recibe los datos.
6. El frontend muestra los resultados al usuario.
7. El usuario selecciona un vídeo y comienza su reproducción.

---

## 3. Arquitectura cliente-servidor

YouTube utiliza una arquitectura basada en la comunicación entre un **cliente** y diferentes servicios del lado del **servidor**.

### Cliente / Frontend

El cliente es principalmente el navegador web del usuario.

En el frontend se ejecutan elementos como:

- HTML.
- CSS.
- JavaScript.
- Interfaz de usuario.
- Buscador.
- Lista de vídeos.
- Botones y controles.
- Reproductor de vídeo.

El navegador se encarga de mostrar la información y de responder a las acciones realizadas por el usuario.

### Servidor / Backend

El backend se ejecuta en los servidores de YouTube.

Entre sus funciones se encuentran:

- Recibir peticiones de los clientes.
- Procesar las búsquedas.
- Obtener información sobre vídeos.
- Gestionar usuarios y cuentas.
- Proporcionar datos al frontend.
- Gestionar diferentes servicios relacionados con la reproducción de vídeos.

El backend no se ejecuta directamente en el ordenador del usuario, sino en los servidores de la plataforma.

---

