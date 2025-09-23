# 🎉 Sistema Cena de Fin de Año

## 1. Supabase
1. Crear proyecto en [Supabase](https://supabase.com).
2. Ejecutar en el SQL Editor:

```sql
-- ver script completo en el asistente
Copiar:

SUPABASE_URL

anon key

2. Apps Script (para enviar mails con QR)

En Google Drive → Nuevo → Apps Script.

Pegar el script de envío (usa Gmail).

Deploy → Web App (cualquiera con link puede acceder).

Copiar la URL y ponerla en index.html → APP_SCRIPT_URL.

3. GitHub Pages

Subir los archivos index.html, checkin.html, sorteo.html.

Activar GitHub Pages (branch main, folder /).

Usar la URL pública para probar.

4. Flujo

Registro → guarda invitado en Supabase → dispara Apps Script → envía QR al correo.

Invitado llega con QR → abre checkin.html?codigo=XXX.

Controlador mete PIN → marca asistencia o rechazo.

Sorteos → sorteo.html, sin repetir ganadores.