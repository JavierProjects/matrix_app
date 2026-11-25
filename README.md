# El poder secreto de las matrices

**Mensajes cifrados, imágenes limpias y secretos visuales.** Presentación interactiva y tres demostraciones para el evento *Ciencias básicas en acción: integración interdisciplinaria para la innovación en ingeniería*, de la carrera de Ingeniería en Tecnologías de la Información y Comunicaciones (ITICs) del ITSOEH.

## Abrir la presentación

1. Clona el repositorio y entra en la carpeta del proyecto.

   ```bash
   git clone https://github.com/JavierProjects/matrix_app.git
   cd matrix_app
   ```

2. Abre [presentacion.html](./presentacion.html) con doble clic. En macOS también puedes ejecutar `open presentacion.html` desde la terminal.
3. Pulsa **Pantalla completa** para proyectar. Usa **←** y **→** para recorrer las diez diapositivas o elige una en la lista de la barra inferior.

Después de clonar el proyecto, la presentación y las tres aplicaciones funcionan sin internet. Todo se ejecuta en el navegador. Los botones de las diapositivas abren las demostraciones en la misma pestaña. El botón **Presentación** regresa a la diapositiva de origen, incluso si visitas otra demostración en el recorrido.

## Demostraciones

| Aplicación | Qué puedes probar |
| --- | --- |
| [Cifrado matricial](./index.html) | Escribe `HOL` y pulsa **Cifrar mensaje**. La matriz de 3 × 3 lo transforma en `H!L`. Explora los cálculos de cada bloque y usa la matriz inversa módulo 33 para recuperar las letras. |
| [Filtros de video](./filtros-video.html) | Pausa el video del robot VEX cerca de **0:37**. Agrega ruido sal y pimienta y compara los filtros de promedio, gaussiano y mediana con ventanas de **3 × 3**, **5 × 5** y **7 × 7**. La lupa muestra la misma región antes y después del filtrado. |
| [Criptografía visual](./criptografia-visual.html) | Usa el logo de ejemplo o carga una imagen. La app la convierte en semitono y genera tres sombras. Empieza con **U2 + U3** y agrega **U1** para revelar el secreto. Compara la superposición **OR** con **XOR** o descarga las sombras en PNG para imprimirlas en transparencias a la misma escala. |

## Archivos y uso sin conexión

Mantén los cuatro archivos HTML juntos al copiar el proyecto a otra computadora. `presentacion.html` es el punto de entrada de la feria e `index.html` abre directamente el laboratorio de cifrado.

La carpeta [imagenes](./imagenes/) contiene los logos institucionales. La página de filtros incorpora una copia del video de VEX con audio para la demostración local. Si dispones del MP4 original y sirves el proyecto por HTTP, puedes colocarlo en `imagenes/VEX U ITICs.mp4`. La aplicación usa la copia integrada cuando el original no está disponible.

## Participantes

- Valera Montesinos Juan David
- Perez Mendoza Christian
- Dr. Cuadros Romero Francisco Javier
