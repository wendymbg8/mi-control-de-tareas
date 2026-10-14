MI CONTROL DE TAREAS — CONFIGURACIÓN GRATUITA PARA MAC + IPHONE

QUÉ HACE ESTA VERSIÓN
- Es una web app estática que se puede alojar gratis en GitHub Pages.
- Los registros y las fotografías se guardan localmente en el navegador de cada dispositivo (IndexedDB).
- NO sincroniza datos entre Mac y iPhone. Cada dispositivo mantiene sus propios registros.
- Incluye copia completa exportable/importable desde “Copias e informes”.
- Se puede añadir a la pantalla de inicio del iPhone y su interfaz básica puede abrirse offline tras la primera carga, si el navegador conserva el almacenamiento.

PUBLICAR GRATIS CON GITHUB PAGES
1. Entra en https://github.com y crea una cuenta gratuita o inicia sesión.
2. Crea un repositorio nuevo. Puedes llamarlo mi-control-de-tareas. Si aparece la opción, déjalo público.
3. Sube TODOS los archivos de esta carpeta a la raíz del repositorio: index.html, manifest.webmanifest, sw.js, icon-192.png e icon-512.png.
4. En el repositorio, entra en Settings > Pages.
5. En “Build and deployment”, elige “Deploy from a branch”; selecciona la rama main y la carpeta /(root), y guarda.
6. Espera a que GitHub Pages publique el sitio. En Settings > Pages aparecerá la dirección pública del sitio. Ábrela y prueba que puedes registrar una foto y cerrar/reabrir.

AÑADIR AL IPHONE
1. Abre la dirección publicada usando Safari en el iPhone (no una vista previa de mensajería).
2. Pulsa Compartir.
3. Elige “Añadir a pantalla de inicio”. Si aparece la opción, activa “Abrir como app web”.
4. Pulsa Añadir. Abre la app desde el nuevo icono.
5. Haz una copia de seguridad inicial de prueba y confirma que puedes exportarla.

USO EN MAC
1. Abre la misma dirección publicada en Chrome o Safari.
2. Registra las tareas desde ese navegador. La primera visita crea un almacén local independiente del iPhone.

TRANSFERIR DATOS ENTRE DISPOSITIVOS (MANUAL)
1. En el dispositivo de origen, abre la app y ve a “Copias e informes”.
2. Pulsa “Descargar copia completa”. Guarda el archivo JSON en Archivos/iCloud Drive o transfiérelo mediante AirDrop.
3. En el otro dispositivo, abre la misma web app, entra en “Copias e informes” y selecciona “Restaurar una copia completa”.
4. ATENCIÓN: restaurar reemplaza los datos que existan en ese navegador. Antes, exporta una copia de seguridad de destino por si necesitas recuperarlos.

IMPORTANTE SOBRE PRIVACIDAD Y COPIAS
- GitHub Pages aloja el código de la app, no recibe las fotos ni los registros que añadas dentro de la app.
- Los datos son independientes por navegador y dispositivo. Abrir el sitio en Safari y Chrome en el mismo Mac también puede crear almacenes distintos.
- No borres los datos del sitio/navegador si no tienes una copia reciente.
- La copia completa JSON incluye las fotos en formato codificado; puede ser grande si guardas muchas imágenes. Guarda copias en una ubicación segura.
- La persistencia del navegador reduce el riesgo de eliminación automática, pero no sustituye a las copias de seguridad.
- Para mantener el servicio sin coste, usa GitHub Pages como alojamiento estático. No hace falta contratar dominio ni servidor.
