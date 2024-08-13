## Guía para Contribuir a los Retos Semanales

### Paso 1: Hacer un Fork del Repositorio

1. **Visita el Repositorio Original:**
   * Navega al repositorio original en GitHub `https://github.com/marceloanton/retos-algoritmos-3`
2. **Haz clic en el botón "Fork":**
   * En la esquina superior derecha de la página del repositorio, encontrarás el botón "Fork". Haz clic en él para crear una copia del repositorio en tu cuenta de GitHub.

### Paso 2: Clonar el Fork en Tu Computadora

1. **Copia la URL del Fork:**
   * Ve a tu repositorio forked y copia la URL. Será algo como `https://github.com/tu-usuario/retos-algoritmos-3.git`
2. **Clona el Repositorio en Tu Computadora:**
   * Abre una terminal y ejecuta el siguiente comando:

     ```
     git clone https://github.com/tu-usuario/retos-algoritmos-3.git
     ```
   * Esto descargará el repositorio en tu computadora.

### Paso 3: Crear una Nueva Rama para Tu Solución

1. **Navega a la Carpeta del Proyecto:**
   * Usa el comando `cd` para entrar en la carpeta del repositorio clonado:

     ```
     cd retos-algoritmos-3
     ```
2. **Crea una Nueva Rama para el Reto de la Semana:**
   * Reemplaza `semana-1-solucion` con el nombre adecuado para la semana correspondiente.
   * Ejecuta el siguiente comando:

     ```
     git checkout -b semana-3-solucion
     ```
   * Esto crea una nueva rama y te cambia a ella.

### Paso 4: Desarrolla Tu Solución

1. **Escribe Tu Código:**
   * Crea una subcarpeta con tu nombre o nombre de usuario de GitHub dentro de la carpeta de la semana correspondiente  `semana-1/tu-nombre/solucion.java`
   * Escribe tu solución en el archivo `solucion.java` (o el nombre que prefieras).

### Paso 5: Guardar y Subir Cambios

1. **Añadir Cambios al Repositorio Local:**
   * Guarda tus cambios y añádelos al área de preparación:

     ```
     git add .
     ```
2. **Hacer Commit de Tus Cambios:**
   * Realiza un commit con un mensaje descriptivo:
     ```
     git commit -m "Solución semana 1"
     ```
3. **Subir Cambios a Tu Repositorio en GitHub:**
   * Empuja tus cambios a tu fork en GitHub:
     ```
     git push origin semana-1-solucion
     ```

### Paso 6: Crear un Pull Request (PR)

1. **Dirígete al Repositorio Original en GitHub:**
   * Abre el repositorio original y verás un mensaje que indica que has subido recientemente cambios a una rama.
2. **Inicia un Pull Request:**
   * Haz clic en "Compare & pull request" para iniciar el PR.
   * Asegúrate de que estás comparando tu rama `semana-1-solucion` con la rama principal del repositorio original.
3. **Completa los Detalles del PR:**
   * Escribe una descripción clara de tu solución y cualquier consideración adicional.
   * Si es necesario, proporciona instrucciones sobre cómo probar tu código.
4. **Envíalo para Revisión:**
   * Haz clic en "Create pull request" para enviar tu PR.

### Paso 7: Revisión y Feedback

1. **Espera la Revisión:**
   * Los instructores revisarán tu PR y pueden dejar comentarios o sugerencias.
   * Responde a los comentarios y realiza cambios adicionales si es necesario.
2. **Fusión del PR:**
   * Una vez aprobado, tu PR será fusionado al repositorio original.
