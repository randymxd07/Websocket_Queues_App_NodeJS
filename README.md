# Aplicación de Colas con Socket.io

Este proyecto se trata de una aplicación diseñada para simplificar y optimizar la gestión de colas en cualquier entorno, ya sea en instituciones gubernamentales, oficinas, centros de atención al cliente o cualquier lugar donde se requiera un sistema eficiente de atención por turnos.

Mejora la experiencia del usuario al reducir los tiempos de espera, brinda transparencia en la gestión de colas y optimiza la eficiencia operativa para las organizaciones que la implementan. Esta aplicación contribuye a la modernización de los procesos de atención al cliente, proporcionando una solución fácil y conveniente para la gestión de colas.

Un servidor de Websockets usando Node, Express y Socket.io


# Instalación

1. Instala las dependencias necesarias para correr el proyecto.

con yarn:
```
yarn install
```

con npm:
```
npm install
```

2. Copia y pega el ```.env.template``` y renombralo a ```.env``` ahí debes definir el puerto en el que quieres que corra la aplicación.

```
PORT=8080
```

3. Una vez que hayas instalado las dependencias y configurado la aplicación podemos correr la aplicación.

con yarn:
```
yarn start
```

con npm:
```
npm run start
```

# Nota

Para utilizar la aplicacion debes abrirla en multiples ventanas o navegadores para simular que hay escritorios y otros que hagan de clientes, la gracia es que desde una pantalla se atiendan los clientes y desde otra los clientes puedan visualizar los turnos actuales y a que escritorio van a ir.