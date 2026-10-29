# Focus Flow

Espacio local de estudio en un único `index.html`. No necesita Node.js, npm, servidor ni cuenta. Ábrelo en un navegador moderno; los proyectos, tareas y resúmenes se guardan en `localStorage`, y los archivos en `IndexedDB`.

## Funciones

- Proyectos y biblioteca de archivos local con búsqueda, descarga y borrado.
- Agenda mensual con tareas fechadas.
- Resúmenes con modos de teoría, práctica, examen y repaso visual con imágenes y vídeos.
- Exportación del espacio completo o de un proyecto como paquete `.estudio` cifrado con AES-GCM y clave derivada mediante PBKDF2.
- Importación y combinación de paquetes cifrados. Comparte el archivo y la clave por canales distintos.

## Privacidad y límites

No hay sincronización ni servidor: para mover datos entre equipos, exporta e importa el paquete manualmente. El navegador no cifra los datos locales en reposo; alguien con acceso a tu mismo perfil del navegador o dispositivo podría verlos. Usa una cuenta del sistema protegida y conserva los paquetes cifrados en un lugar seguro. La capacidad de archivos depende del espacio que permita el navegador.

Tailwind, Lucide, GSAP y la fuente tipográfica se cargan desde CDN, por lo que la presentación completa requiere conexión a Internet. El HTML y los datos locales se pueden abrir sin instalar herramientas.
