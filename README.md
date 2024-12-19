# ProyectoCasaEmpenho

## Descripción
Este proyecto es una aplicación ejecutable para la gestión de casas de empeño. 
Está diseñado para funcionar sin necesidad de instalar dependencias adicionales, utilizando SQLite para almacenar datos importantes y guardando respaldos automáticamente en una carpeta de OneDrive para mayor seguridad.

### Características principales:
- Autenticación de usuario (credenciales iniciales proporcionadas más abajo).
- Sistema de respaldo automático en OneDrive.
- Base de datos local (SQLite) para garantizar la persistencia de los datos.

---

## Requisitos
- **OneDrive:** El ejecutable debe colocarse en una carpeta de OneDrive para que las rutas relativas funcionen correctamente y se guarden los respaldos de forma automática.

---

## Instrucciones de uso

1. **Ubicación del archivo:**
   - Coloca el archivo ejecutable en tu carpeta de OneDrive.
   - Si no existe una carpeta llamada `Respaldo` en OneDrive, el sistema la creará automáticamente para guardar los backups.

2. **Ejecutar la aplicación:**
   - Haz doble clic en el archivo ejecutable. No es necesario instalar Python, Flask ni ninguna dependencia adicional.

3. **Iniciar sesión:**
   - Usa las siguientes credenciales para ingresar al sistema:
     - **Usuario:** `PANDA`
     - **Contraseña:** `13250152`

4. **Respaldo automático:**
   - La aplicación creará respaldos automáticamente o manual en la carpeta `respaldo` dentro de OneDrive.

---

## Notas importantes
- Si mueves el archivo ejecutable a otra computadora, asegúrate de colocarlo también en una carpeta de OneDrive para que el sistema de respaldo funcione correctamente.
- La base de datos local (SQLite) se guardará junto con los respaldos para evitar la pérdida de datos en caso de formateo o falla del equipo.

---

## Contacto y soporte
Si encuentras algún problema o necesitas soporte técnico, no dudes en abrir un issue en el repositorio o contactarme directamente.

---

## Licencia
Este proyecto está bajo la licencia MIT. Siente la libertad de usarlo y modificarlo según sea necesario.
