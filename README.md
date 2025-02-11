Este proyecto es una aplicación web simple para realizar sorteos de "Amigo Secreto". Permite a los usuarios ingresar nombres en una lista y luego seleccionar aleatoriamente un nombre como el amigo secreto.
Instalación
  Clonar el repositorio:
  git clone https://github.com/tu_usuario/amigo-secreto.git
Navegar al directorio del proyecto:
  cd amigo-secreto
  No se requieren instalaciones adicionales, ya que es un proyecto basado en HTML, CSS y JavaScript puro.
Dependencias
  Este proyecto no utiliza frameworks ni librerías externas, solo tecnologías estándar:
  HTML
  CSS3
  JavaScript 
Cómo ejecutar el proyecto
  Asegúrate de que tienes un navegador web actualizado.
  Abre el archivo index.html en tu navegador:
  Puedes hacer doble clic en el archivo index.html.
  O ejecutar un servidor local (opcional, recomendado para evitar restricciones de CORS):
  npx serve .
  Interactúa con la interfaz agregando nombres y realizando el sorteo.
Posibles problemas y soluciones
  1. El botón "Añadir" no funciona
  Asegúrate de que app.js está correctamente enlazado en index.html:
  <script src="app.js" defer></script>
  Verifica que app.js se encuentra en el mismo directorio que index.html.
  2. El botón "Sortear amigo" no responde
  Asegúrate de haber ingresado al menos dos nombres antes de hacer clic en sortear.
  Revisa la consola del navegador (F12 → "Consola") en busca de errores.
  3. Los nombres no se agregan a la lista
  Asegúrate de que el campo de entrada no esté vacío antes de hacer clic en "Añadir".
  Verifica que no estás ingresando nombres duplicados, ya que están restringidos.
  Autor
  Desarrollado por Andrea Gregorio de las Heras
