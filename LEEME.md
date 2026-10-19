# Pomodoro de Estudio — app Android

## Opción A: que GitHub te genere el APK (sin instalar nada)
1. Crea una cuenta en github.com y un repositorio nuevo (puede ser privado).
2. En el repositorio: "Add file" > "Upload files" y arrastra TODO el contenido de esta carpeta
   (incluida la carpeta oculta .github). Pulsa "Commit changes".
   Si la pestaña Actions no muestra nada, es que la carpeta oculta .github no se subió:
   usa "Add file" > "Create new file", nómbralo .github/workflows/build-apk.yml y pega
   el contenido de workflow-copia/build-apk.yml.
3. Ve a la pestaña "Actions". Se ejecuta "Compilar APK" (tarda ~3-5 min).
4. Cuando tenga la marca verde, ábrelo y descarga "Pomodoro-APK" en la sección Artifacts.
   Es un .zip; adentro está app-release.apk.
5. Pásalo al celular, ábrelo y permite "instalar apps de origen desconocido".

## Opción B: Android Studio
Abre esta carpeta en Android Studio y usa Build > Build APK(s).

La interfaz de la app está en app/src/main/assets/index.html.
