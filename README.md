# Graphy - Sistema de Recomendación de Productos

## Descripción del Proyecto

Graphy es una aplicación web innovadora diseñada para mejorar la experiencia de compra en línea mediante un sistema de recomendación de productos personalizado. Utilizando un algoritmo modificado de Prim, Graphy ofrece recomendaciones precisas basadas en las preferencias del usuario y el historial de compras.

## Características Principales

- Sistema de recomendación basado en el algoritmo de Prim modificado
- Interfaz de usuario intuitiva y responsiva desarrollada con Vue.js y Tailwind CSS
- Backend robusto implementado con Microsoft Azure Functions
- Base de datos NoSQL en MongoDB para almacenamiento eficiente de datos
- API RESTful para integración con sistemas externos

## Tecnologías Utilizadas

- Frontend: Vue.js, Tailwind CSS
- Backend: Microsoft Azure Functions
- Base de Datos: MongoDB
- Otros: Git, GitHub

## Instalación

Para instalar y ejecutar Graphy en tu entorno local, sigue estos pasos:

1. Clona el repositorio:
   ```
   git clone https://github.com/tu-usuario/graphy-app.git
   ```

2. Navega al directorio del proyecto:
   ```
   cd graphy-app
   ```

3. Instala las dependencias:
   ```
   npm install
   ```

4. Configura las variables de entorno necesarias (ver sección de Configuración).

5. Inicia la aplicación:
   ```
   npm run dev
   ```

## Configuración

Crea un archivo `.env` en la raíz del proyecto y añade las siguientes variables:

```
VUE_APP_API_URL=<URL de tu API>
VUE_APP_MONGODB_URI=<URI de tu base de datos MongoDB>
```

## Uso

Una vez instalado y configurado, puedes acceder a Graphy a través de `http://localhost:8080` (o el puerto que hayas configurado).

## Contribución

Agradecemos las contribuciones a Graphy. Si deseas contribuir, por favor:

1. Haz un fork del repositorio
2. Crea una nueva rama (`git checkout -b feature/AmazingFeature`)
3. Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Haz push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request


