# Las aventuras de Kristian

Juego de plataformas 2D hecho en un solo archivo HTML (HTML + CSS + JavaScript, sin dependencias).

## Características

- 21 niveles: bosque, ciudad y más biomas generados.
- **Triple salto** y saltos sobre los enemigos para derrotarlos.
- Nivel 20: pelea contra un jefe.
- Nivel 21: escape contra reloj, con checkpoints y un perseguidor.
- Música y efectos de sonido generados por código, con opción para desactivarlos.
- Controles táctiles en pantalla y teclado, con teclas configurables desde el menú.
- Selector de nivel y contador de FPS opcional.

## Cómo jugar

**En el navegador:** abre `index.html` (o la versión de `apk/www/index.html`) en cualquier navegador moderno.

**En Android:** descarga el APK desde la sección [Releases](../../releases). Si Android pide permiso, activa la instalación de apps desde el navegador.

**Controles por defecto:** flecha izquierda / derecha para moverte y flecha arriba para saltar (puedes cambiarlas en *Configuración*). En móvil usa los botones de la pantalla.

## Crear el APK tú mismo

La carpeta `apk/` contiene un proyecto [Capacitor](https://capacitorjs.com/). El APK se compila automáticamente con GitHub Actions: ve a la pestaña **Actions → Construir APK → Run workflow**. Al terminar, el APK aparece como una nueva release.

Para actualizar el juego en el APK, cambia `apk/www/index.html` y vuelve a ejecutar el workflow.

## Licencia

Código abierto bajo la [licencia MIT](LICENSE). Puedes usarlo, modificarlo y compartirlo, manteniendo el aviso de copyright.

Creado por [@KristianCraft](https://github.com/KristianCraft).
