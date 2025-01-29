# PROYECTO: Carrito de Compras - Creando el Carrito, introducción a Hooks y más

Este proyecto es una implementación de un carrito de compras utilizando React. A lo largo del desarrollo, se exploran conceptos fundamentales como componentes, JSX, Hooks, State, Props, y más. Además, se implementan funcionalidades avanzadas como la persistencia del carrito en el LocalStorage y la optimización del rendimiento con `useMemo`.

## Estructura del Proyecto

El proyecto está organizado en una serie de secciones que cubren diferentes aspectos de React y su aplicación en la creación de un carrito de compras:

1. **Estructura de archivos de React**
2. **Copiar el código HTML estático a React**
3. **Escribir código CSS en React**
4. **Componentes en React**
5. **JSX**
6. **Renombrar class a className en el proyecto**
7. **Crear un Componente para cada Guitarra**
8. **Introducción a los React Hooks**
9. **State en React y useState**
10. **Reglas de los Hooks**
11. **useEffect**
12. **Añadir los Productos al State**
13. **Iterar sobre los Productos en React**
14. **Props**
15. **Mostrar la Información de cada Guitarra**
16. **Eventos en JSX**
17. **Crear un State de Carrito**
18. **Agregar Guitarras al Carrito**
19. **Detectar si un elemento existe en el carrito**
20. **Agregar Guitarras al Carrito con Cantidad**
21. **Incrementar cantidad si un artículo ya estaba agregado**
22. **Mostrar los Contenidos del carrito**
23. **Detectar si el carrito tiene algo o está vacío**
24. **State derivado**
25. **Calcular el Total a pagar**
26. **useMemo para mejorar el performance del código**
27. **Eliminar Artículos del Carrito**
28. **Crear una Función para Incrementar las cantidades**
29. **Agregar la función de Limpiar Carrito**
30. **Carrito persistente con LocalStorage - Almacenar**
31. **Carrito persistente con LocalStorage - Recuperar los productos y mostrarlos**

## Características Principales

- **Componentes Reutilizables**: Se crean componentes para cada guitarra, lo que permite una fácil reutilización y mantenimiento del código.
- **Gestión del Estado con Hooks**: Se utiliza `useState` para manejar el estado del carrito y `useEffect` para efectos secundarios como la persistencia en LocalStorage.
- **Persistencia del Carrito**: El carrito se almacena en el LocalStorage del navegador, permitiendo que los datos persistan incluso después de recargar la página.
- **Optimización del Rendimiento**: Se emplea `useMemo` para evitar cálculos innecesarios y mejorar el rendimiento de la aplicación.
- **Funcionalidades del Carrito**: Incluye la capacidad de agregar, eliminar, incrementar y limpiar artículos del carrito, así como calcular el total a pagar.

## Cómo Ejecutar el Proyecto

1. Clona el repositorio en tu máquina local.
2. Instala las dependencias necesarias con `npm install`.
3. Ejecuta el proyecto con `npm start`.
4. Abre tu navegador y visita `http://localhost:3000` para ver la aplicación en funcionamiento.

## Contribuciones

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama con tu contribución (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añade nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).

---

¡Gracias por revisar este proyecto! Si tienes alguna pregunta o sugerencia, no dudes en contactarme.