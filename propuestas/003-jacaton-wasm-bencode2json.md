# Propuesta de Sesión

**Título de la sesión:**

Jacatón: WASM con Rust – De Bencode a JSON en el navegador

**Descripción:**

Sesión grupal de 4 horas (de 10:00 a 14:00) para aprender a integrar Rust en el navegador usando WebAssembly (WASM). El objetivo es desarrollar una pequeña aplicación web que permita subir un fichero en formato binario bencode y convertirlo a JSON usando la librería [bencode2json](https://github.com/torrust/bencode2json). La actividad está orientada a grupos de máximo 5 personas y es ideal para quienes quieran aprender sobre WASM, interoperabilidad entre Rust y JavaScript, y reutilización de librerías de Rust en el cliente.

**Pasos propuestos para la actividad:**

- Breve introducción a WASM y cómo compilar Rust para el navegador.
- Clonar y preparar el entorno de trabajo.
- Integrar la librería bencode2json en un proyecto Rust orientado a WASM.
- Crear una interfaz web sencilla (HTML/JS) para subir el fichero bencode y mostrar el resultado en JSON.
- Compilar y enlazar el código Rust/WASM con la web.
- Pruebas y mejoras colaborativas.
- Discusión final sobre retos, aprendizajes y posibles mejoras.

**Proponente:**

@josecelano

**Formato:**

Jacatón grupal (máx. 5 personas). Formato mixto: presencial y online.

**Duración estimada:**

4 horas (10:00–14:00)

**Estado:**

Propuesta definitiva

**Notas adicionales:**

No se requieren conocimientos previos de WASM, pero sí interés en aprender y colaborar. La sesión se realizará en formato mixto: presencial y online. Se puede realizar en modo "vibe coding" (colaborativo y relajado), pero revisando y aprendiendo del código final generado entre todos.

---

## Detalle de los pasos propuestos para la actividad

1. **Introducción a WASM y Rust en el navegador**
   - Explicación breve de qué es WASM y cómo Rust puede compilarse a este formato.
   - Ejemplos de casos de uso y ventajas.
2. **Preparación del entorno**
   - Instalación de las herramientas necesarias (Rust, wasm-pack, Node.js, etc.).
   - Clonado del repositorio base.
3. **Integración de la librería bencode2json**
   - Añadir la dependencia al proyecto Rust.
   - Breve repaso de la API de la librería.
4. **Desarrollo de la interfaz web**
   - Crear una página HTML/JS para subir archivos y mostrar resultados.
   - Conectar la lógica WASM/Rust con la interfaz.
5. **Compilación y enlace**
   - Compilar el proyecto Rust a WASM.
   - Integrar el bundle generado en la web.
6. **Pruebas y mejoras**
   - Subir archivos de ejemplo, depurar y mejorar la experiencia.
   - Añadir validaciones y mensajes de error.
7. **Revisión y discusión final**
   - Analizar el código generado, compartir aprendizajes y posibles mejoras para futuras sesiones.
