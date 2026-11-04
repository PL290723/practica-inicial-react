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

## Registro de pruebas (Etapa básica)
| Prueba | Resultado Esperado | Obtenido | Estado | Corrección (si aplica) |
| :--- | :--- | :--- | :--- | :--- |
| P01 Inicio | Se muestra Ana y la posición 1 de 3. | | | |
| P02 Siguiente | Desde Ana, Siguiente muestra Luis y 2 de 3. | | | |
| P03 Límite sup. | Desde María, Siguiente muestra Ana. | | | |
| P04 Límite inf. | Desde Ana, Anterior muestra María. | | | |
| P05 Aleatorio | Cambia a otra válida (repetir 10 veces). | | | |
| P06 Un registro | Controles mantienen el registro, sin errores. | | | |
| P07 Sin registros| Muestra mensaje sin controles. | | | |
| P08 Ampliación | Navegación con los 5 objetos extra. | | | |
| P09 Interfaz | 3 anchos, teclado y textos ajustados. | | | |
| P10 Compilación | npm run build sin errores en consola. | | | |