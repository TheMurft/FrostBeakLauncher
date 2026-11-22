# FrostBeakLauncher

## Publicar una actualización

1. Cambia `version` en `launcher-version.json` y actualiza la versión de `package.json` en el proyecto del launcher.
2. Genera el instalador de Windows con el nombre exacto `FrostBeak Launcher-win-x64.exe`.
3. Crea un Release en este repositorio y adjunta ese instalador.
4. Publica el cambio de `launcher-version.json` en `main`.

Al abrirse, el launcher compara su versión con este archivo. Si la versión remota es mayor, pregunta si quieres actualizar o continuar. Si no hay conexión, abre normalmente.
