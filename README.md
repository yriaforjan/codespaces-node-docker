# Hola Docker en GitHub Codespaces 🚀

Este proyecto es una introducción práctica a **Docker** utilizando **Node.js** y **Express**, ejecutado íntegramente en la nube mediante **GitHub Codespaces**.

## ⚙️ Tecnologías utilizadas
* **Node.js**: Entorno de ejecución.
* **Express**: Framework web.
* **Docker**: Contenedores.
* **GitHub Codespaces**: Entorno de desarrollo en la nube.

---

## 📋 Requisitos
No necesitas instalar nada localmente. Solo necesitas:
* Una cuenta de GitHub.
* El entorno de Codespaces.

---

## 🛠️ Estructura del Proyecto
* `index.js`: Servidor web básico con Express.
* `package.json`: Definición de dependencias y scripts de Node.js.
* `Dockerfile`: Instrucciones para construir la imagen del contenedor.

---

## 🚀 Pasos para ejecutar

### 1. Construir la imagen de Docker
Abre la terminal en tu Codespace y ejecuta el siguiente comando para crear la imagen basada en el `Dockerfile`:

```bash
docker build -t hola-node .
```

### 2. Correr el contenedor
Una vez creada la imagen, levanta el contenedor mapeando el puerto 3000:

```bash
docker run -p 3000:3000 hola-node
```

### 3. Ver la aplicación
* Al ejecutar el comando anterior, GitHub Codespaces detectará el puerto.
* Haz clic en el botón "Open in Browser" que aparecerá en la esquina inferior derecha o ve a la pestaña Ports y abre el puerto 3000.

---

## 🔍 Comandos Útiles de Docker

| Comando | Descripción |
| :--- | :--- |
| `docker ps` | Listar contenedores activos. |
| `docker images` | Listar imágenes creadas localmente. |
| `docker stop <ID>` | Detener un contenedor en ejecución. |

---

## 📄 Licencia
Este proyecto es de código abierto y está bajo la [Licencia MIT](https://opensource.org/licenses/MIT).

---

## 👩🏼‍💻 Autor  
Proyecto realizado como parte de la práctica de Docker en GitHub Codespaces en la asignatura de Despliegue de Aplicaciones Web.

