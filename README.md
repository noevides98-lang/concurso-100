# Concurso 100

Ocho participantes individuales con pulsadores y banco editable. Configurado para Firebase concurso-100.

## Publicar
Sube index.html, assets/ y los archivos .md y .json a la raíz del repositorio. No subas el ZIP. En Settings > Pages selecciona Deploy from a branch, main y /(root).

## Probar
Abre la página y crea una sala desde la computadora. Copia el enlace para jugadores y ábrelo en dos teléfonos. Ingresa nombres distintos, activa los pulsadores y pulsa en ambos. Solo debe aparecer un ganador. Revela una respuesta para sumar puntos; marca Error para bloquear al ganador durante esa pregunta. Prueba también la ventana de proyección.

Firebase requiere Authentication anónimo habilitado y las reglas de database.rules.json publicadas. El límite de ocho jugadores se comprueba en la interfaz; las reglas todavía no lo imponen. Las respuestas ocultas están descargadas en los clientes y esta versión es para un concurso recreativo de confianza. No incluye todavía cronómetro automático, QR ni efectos de sonido. Las preguntas incluidas son ejemplos inventados.

Las preguntas editadas se guardan por sala. Conserva el enlace y usa el mismo navegador del presentador para mantener su identidad.

Consulta PERSONALIZAR.md para sustituir las imágenes.
