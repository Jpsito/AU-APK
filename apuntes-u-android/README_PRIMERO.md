# Apuntes U — proyecto Android nativo

Esto es tu app envuelta con Capacitor para poder compilar un APK real.
No necesitás instalar Android Studio: GitHub va a compilar el APK por vos.

Seguí los pasos que te pasó Claude en el chat. Resumen rápido:

1. Creá un repositorio nuevo y PÚBLICO en https://github.com/new (sin plantilla, sin README).
2. Abrí ese repo vacío y entrá a la pestaña "Code" → botón verde "Code" → "Codespaces" → "Create codespace on main".
3. Cuando cargue el editor (es como VS Code, pero en el navegador), arrastrá TODA esta carpeta
   (apuntes-u-android, con todo su contenido) al panel de archivos de la izquierda.
4. Abrí una terminal (menú Terminal → New Terminal) y corré:
       git add -A
       git commit -m "primera version nativa"
       git push
5. Andá a la pestaña "Actions" de tu repositorio en GitHub. Va a aparecer un flujo
   corriendo solo ("Compilar APK"). Esperá unos 3-5 minutos.
6. Cuando termine (tilde verde), entrá a esa ejecución y bajá el archivo
   "apuntes-u-apk" que aparece en "Artifacts". Es un .zip: adentro está tu app-debug.apk.
7. Pasá ese .apk a tu celular (por WhatsApp a vos mismo, Google Drive, cable, lo que sea)
   y instalalo. Android te va a avisar que es de un "origen desconocido": es normal,
   dale a "instalar de todos modos" (es tu propio APK, compilado por vos).
