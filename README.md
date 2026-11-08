# Práctica inicial de React: Aplicación de testimonios

**Materia:** Ingeniería de Software - Unidad 3
**Equipo:** 
- Paulo Cesar Rivera Lara
- Jairo Antonio Melgar Obrajero

## Entorno y Versiones
- **Node.js:** v24.22.0
- **npm:** 11.19.1

## Registro de tareas y roles (Kanban)
*Historia de Usuario: Como visitante, quiero consultar testimonios mediante controles de navegación.*

| Tarea | Puntos | Conductor | Observador | Estado | Revisión Externa |
| :--- | :---: | :--- | :--- | :--- | :--- |
| 1. Entorno (Vite, limpieza y archivos) | | | | Pendiente | |
| 2. Datos (data.js y 5 registros) | | | | Pendiente | |
| 3. Tarjeta (Testimonial.jsx) | | | | Pendiente | |
| 4. Navegación (App.jsx, Controls, useState) | | | | Pendiente | |
| 5. Estilos (styles.css y responsivo) | | | | Pendiente | |
| 6. Verificación (build y P01-P10) | | | | Pendiente | |

## Registro de Pruebas (Etapa Básica)
| Prueba | Resultado Esperado | Obtenido | Estado | Corrección (si aplica) |
| :--- | :--- | :--- | :--- | :--- |
| P01 Inicio | Se muestra Ana y la posición 1 de 5. | Se muestra Ana y 1 de 5. | Aprobado | Ninguna. |
| P02 Siguiente | Desde Ana, Siguiente muestra Luis y 2 de 5. | Muestra a Luis correctamente. | Aprobado | Ninguna. |
| P03 Límite sup. | Desde el último, Siguiente muestra Ana. | Regresa a Ana. | Aprobado | Ninguna. |
| P04 Límite inf. | Desde Ana, Anterior muestra al último. | Muestra a Sofía (último). | Aprobado | Ninguna. |
| P05 Aleatorio | Cambia a otra válida (repetir 10 veces). | Selecciona sin repetir el actual. | Aprobado | Ninguna. |
| P06 Un registro | Controles mantienen el registro, sin errores. | Probado temporalmente, sin error. | Aprobado | Ninguna. |
| P07 Sin registros| Muestra mensaje sin controles. | Probado temporalmente, éxito. | Aprobado | Ninguna. |
| P08 Ampliación | Navegación con los 5 objetos extra. | Recorre los 5 testimonios. | Aprobado | Ninguna. |
| P09 Interfaz | 3 anchos, teclado y textos ajustados. | Funciona con Tab y es responsivo. | Aprobado | Ninguna. |
| P10 Compilación | npm run build sin errores en consola. | Compila correctamente a dist. | Aprobado | Ninguna. |