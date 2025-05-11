# Guía de Uso de Xoconodo – Editor de Diagramas v1.5.1

Xoconodo es un editor de diagramas basado en React Flow que permite crear, conectar y personalizar nodos de forma visual. A continuación se describen sus principales componentes y flujos de trabajo.

---

## 1. Interfaz General

- **Encabezado flotante**  
  - **Logo “XOCONODO”** en la esquina superior izquierda.  
  - **Botones “Deshacer” y “Rehacer”** en la esquina superior derecha (Ctrl+Z / Ctrl+Y).

- **Contenedor principal**  
  - **Lienzo React Flow** ocupa la mayor parte de la pantalla.  
  - **Fondo puntillado o de líneas** (configurable).

- **Panel de controles**  
  - **MiniMap** (esquina inferior derecha) para navegación global.  
  - **Controles zoom/flechas** junto al MiniMap.

---

## 2. Panel Izquierdo (“Left Sidebar”)

1. **Añadir nodos**  
   - **Add Node**: crea un nodo genérico con forma, color y borde predeterminados.  
   - **Add Image**: inserta un nodo de imagen desde tu disco.  
   - **Add Concatenate / Result / Download / Capitalizar / Mayúsculas / Minúsculas**: nodos preconfigurados para manipular texto o descargar datos.

2. **Rejilla automática (“Grid”)**  
   - Interruptor para ordenar nodos en círculo y alternar el fondo de líneas.

3. **Recentrar vista**  
   - Centra y ajusta todos los nodos a la vista.

4. **Import / Export**  
   - **Import**: carga un `.json` con nodos, conexiones y posición de la cámara.  
   - **Export**: descarga el diagrama actual como JSON.

5. **Share**  
   - Genera y copia al portapapeles una URL “flow=…” con tu diagrama codificado.

---

## 3. Barra de Herramientas Superior (“Tools Toolbar”)

- **Selección de forma de nodo**  
  – Rectángulo, Círculo o Diamante.  

- **Color de fondo**  
  – Paleta de colores para rellenar nodos.  

- **Color y estilo de borde**  
  – Paleta de colores + opciones “solid”, “dashed”, “dotted” o “none”.

- **Tipo de conexión**  
  – Bezier (con edición), SmoothStep, Step o Straight.

- **Estilo de línea**  
  – Solid, Dashed o Animated Dashed.

- **Duplicar / Eliminar**  
  – Botones para clonación rápida (Ctrl + D) o borrado (Supr).

---

## 4. Área de Lienzo

- **Crear nodos**  
  - Haz clic en “Add Node” o arrastra nodos desde el panel izquierdo.  
  - Haz doble clic sobre un nodo para editar su etiqueta (Enter para guardar, Esc para cancelar).

- **Conectar nodos**  
  - Arrastra desde un “handle” de un nodo (pequeño círculo) hacia otro handle para crear una arista.  
  - Doble clic sobre la etiqueta de la arista para editarla.

- **Nodo de imagen**  
  - Soporta redimensionar arrastrando el pequño manejador que aparece al seleccionar.

- **Nodo funcional**  
  - Concatenar, capitalizar, convertir a mayúsculas/minúsculas, mostrar resultados o descargar contenido.

- **Context menu**  
  - Clic derecho sobre un nodo abre opciones: “Bloquear/Desbloquear” para fijar su posición.

---

## 5. Pan y Zoom

- **Zoom**  
  - Rueda del ratón sobre el lienzo: acerca/aleja centrado en el cursor.  
  - Controles “+” / “–” en la esquina inferior derecha.

- **Paneo (desplazamiento)**  
  - Mantén pulsada la tecla **Alt** y arrastra con el **botón izquierdo** para mover el lienzo libremente.

- **Fit View**  
  - Botón en los controles (ícono de cuadrado) para ajustar todos los nodos a la pantalla.

---

## 6. Atajos Clave

| Acción                 | Atajo                |
| ---------------------- | -------------------- |
| Deshacer               | Ctrl + Z             |
| Rehacer                | Ctrl + Y             |
| Duplicar nodo          | Ctrl + D             |
| Eliminar elemento      | Supr / Backspace     |
| Guardar diagrama (Export) | –                 |

---

## 7. Flujo de Trabajo Sugerido

1. **Diseña** tu diagrama añadiendo nodos desde el panel izquierdo.  
2. **Conecta** los nodos arrastrando handles.  
3. **Personaliza** forma, color y bordes en la barra de herramientas.  
4. **Edita** etiquetas con doble clic.  
5. **Organiza** con auto-layout o manualmente.  
6. **Deshacer/Rehacer** según necesites.  
7. **Exporta** o **comparte** tu diagrama al finalizar.

---

**¡Listo!** Xoconodo te ofrece un entorno poderoso para crear diagramas de flujo, esquemas y procesamientos de datos de manera visual y colaborativa.
