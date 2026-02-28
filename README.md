## ¿Qué es Angular?

Angular es un framework para desarrollar aplicaciones web creado por Google. 
Se utiliza principalmente para construir aplicaciones tipo SPA (Single Page Application), es decir, aplicaciones que funcionan en una sola página y cargan el contenido de forma dinámica sin recargar todo el sitio.

Angular permite trabajar de manera organizada usando componentes, lo que facilita mantener el código ordenado y reutilizar partes del mismo.

---

## ¿Qué herramientas se necesitan instalar?

Para poder trabajar con Angular es necesario instalar lo siguiente:

### 1. Node.js
Es un entorno que permite ejecutar JavaScript fuera del navegador.  
También incluye npm, que es el gestor de paquetes.

Para verificar que está instalado:

node -v
npm -v


---

### 2. Angular CLI
Es la herramienta oficial para crear y administrar proyectos Angular desde la terminal.

Se instala con el siguiente comando:

npm install -g @angular/cli


Para verificar la instalación:

ng version


---

### 3. Editor de código
Se recomienda usar Visual Studio Code porque facilita la programación y tiene buen soporte para Angular.

---

### 4. Navegador web
Un navegador como Google Chrome para poder ejecutar y probar la aplicación.

---

## Crear y ejecutar un proyecto

Para crear un nuevo proyecto:

ng new nombre-del-proyecto


Para ejecutar el proyecto:

cd nombre-del-proyecto
ng serve


Luego abrir en el navegador:

http://localhost:4200

–--