# Ogonam: compilar APK desde un OPPO usando GitHub Actions

Este proyecto ya trae un workflow en:

.github/workflows/build-apk.yml

Ese workflow compila el APK en la nube de GitHub y lo deja como archivo descargable.

## Pasos rápidos desde el OPPO

1. Entra en github.com desde Chrome.
2. Crea un repositorio nuevo llamado Ogonam.
3. Sube el contenido de esta carpeta al repositorio.
4. En GitHub, entra en la pestaña Actions.
5. Abre Build Ogonam APK.
6. Pulsa Run workflow.
7. Espera a que termine.
8. Entra en la ejecución terminada y descarga el artifact Ogonam-debug-apk.
9. Descomprime el ZIP que descarga GitHub.
10. Instala el APK en tu OPPO.

El APK generado será debug. Sirve para instalar y probar en tu móvil.
