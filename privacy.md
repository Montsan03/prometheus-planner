# Prometheus Planner — Privacy Policy

_Effective date: August 5, 2026 · Contact: lperal03@mac.com_

**The short version.** Your planner lives on your device and in your own private iCloud. We run no analytics, show no ads, and use no trackers. Two optional features send specific data out only after you turn them on, and this policy names exactly what they send.

### 1. What stays on your device
- Your pages, tasks, appointments, notes, Apple Pencil ink, expenses, roles, goals and backups are stored locally on your device.
- Handwriting recognition (turning ink into text/tasks) runs entirely on-device using Apple's Vision framework. Your handwriting is never uploaded.
- Notifications (appointment alarms, the daily task digest, the evening day-close reminder) are local; we operate no push servers.
- `.goblin` backup files are created only when you export them (or when auto-backup is enabled) and stay where you put them. They are **not encrypted** — keep them private.

### 2. iCloud (Apple)
If iCloud is enabled, your planner data syncs through your **private iCloud database**, encrypted and controlled by your Apple Account. We, the developer, have no access to it. Apple's own privacy policy governs iCloud.

### 3. Calendar and Reminders
With your permission, the app reads and writes events and reminders using Apple's EventKit **on your device** to keep the planner in sync with the system apps. This data is not transmitted to us or to any third party by the sync itself.

### 4. Optional: Oráculo team connection
If (and only if) you sign in to an Oráculo company workspace:
- Your **email address and password** are sent to our server (`api.oraculo.prometheusih.com`) over HTTPS to authenticate; we store a session token in your device's Keychain.
- Action items assigned to you are downloaded into your planner.
- If you additionally enable the **"Share productivity"** switch (off by default), the app sends: aggregated productivity metrics (tasks completed/remaining today, velocity, energy level, streak, counts of pending A/B and overdue tasks) and the **titles and times of appointments that look like meetings** (matched by keywords such as "meeting", "junta", "call"). Task titles are never sent through this channel.
- Turning the switch off stops these transmissions. Disconnecting the account removes the session from your device.

### 5. Optional: Pythia AI assistant (bring your own key)
Pythia only works if you paste your **own Anthropic API key** (stored in your device's Keychain, never on our servers). When you ask Pythia a question, the app sends to **Anthropic** (api.anthropic.com), under your key and Anthropic's terms: your question and a daily context that can include **task titles, appointment titles and times, overdue-task titles, productivity metrics, and expense amounts by category**. If your question concerns your company workspace and you are signed in to Oráculo, the question text may also be sent to our server to retrieve company context. Don't use Pythia if you don't want this data to leave the device.

### 6. What we do NOT do
- No advertising, no ad identifiers (IDFA), no tracking across apps or websites.
- No third-party analytics or crash-reporting SDKs.
- No sale or sharing of personal data with data brokers.
- No accounts required for the core app.

### 7. Data retention and deletion
- On-device and iCloud data: delete it by deleting content in the app, or removing the app and its iCloud data (iOS Settings → Apple Account → iCloud).
- Oráculo server data (account, metrics, meeting titles): request deletion at the contact email; we delete within 30 days.
- Anthropic receives Pythia requests under your own key; their retention is governed by Anthropic's policies for your account.

### 8. Children
The app is a general-audience productivity tool and does not knowingly collect data from children.

### 9. Changes
We will update this page and the effective date when the policy changes. Material changes will be noted in the app's release notes.

---

# Prometheus Planner — Política de Privacidad

_Fecha de entrada en vigor: 5 de agosto de 2026 · Contacto: lperal03@mac.com_

**La versión corta.** Tu planner vive en tu dispositivo y en tu propio iCloud privado. No usamos analytics, no mostramos anuncios y no usamos rastreadores. Dos funciones opcionales envían datos específicos solo después de que tú las actives, y esta política nombra exactamente qué envían.

### 1. Lo que se queda en tu dispositivo
- Tus páginas, tareas, citas, notas, tinta de Apple Pencil, gastos, roles, metas y respaldos se guardan localmente en tu dispositivo.
- El reconocimiento de escritura (convertir tinta en texto/tareas) ocurre por completo en el dispositivo usando el framework Vision de Apple. Tu escritura nunca se sube.
- Las notificaciones (alarmas de citas, resumen diario de tareas, recordatorio del cierre del día) son locales; no operamos servidores de push.
- Los archivos de respaldo `.goblin` se crean solo cuando los exportas (o activas el respaldo automático) y permanecen donde tú los guardes. **No están cifrados** — mantenlos privados.

### 2. iCloud (Apple)
Si iCloud está activo, tus datos se sincronizan a través de tu **base de datos privada de iCloud**, cifrada y controlada por tu Cuenta Apple. Nosotros, como desarrollador, no tenemos acceso a ella. iCloud se rige por la política de privacidad de Apple.

### 3. Calendario y Recordatorios
Con tu permiso, la app lee y escribe eventos y recordatorios mediante EventKit de Apple **en tu dispositivo**, para mantener el planner sincronizado con las apps del sistema. Esta sincronización no nos transmite datos a nosotros ni a terceros.

### 4. Opcional: conexión de equipo Oráculo
Si (y solo si) inicias sesión en un espacio de empresa Oráculo:
- Tu **correo y contraseña** se envían a nuestro servidor (`api.oraculo.prometheusih.com`) por HTTPS para autenticarte; guardamos un token de sesión en el Keychain de tu dispositivo.
- Los action items asignados a ti se descargan a tu planner.
- Si además activas el interruptor **"Compartir productividad"** (apagado por defecto), la app envía: métricas agregadas de productividad (tareas completadas/restantes hoy, velocity, nivel de energía, racha, conteos de tareas A/B pendientes y atrasadas) y los **títulos y horarios de las citas que parecen juntas** (detectadas por palabras como "junta", "meeting", "llamada"). Los títulos de tus tareas nunca se envían por este canal.
- Apagar el interruptor detiene estos envíos. Desconectar la cuenta elimina la sesión de tu dispositivo.

### 5. Opcional: asistente de IA Pythia (con tu propia clave)
Pythia solo funciona si pegas tu **propia API key de Anthropic** (se guarda en el Keychain de tu dispositivo, nunca en nuestros servidores). Cuando le preguntas algo a Pythia, la app envía a **Anthropic** (api.anthropic.com), con tu clave y bajo los términos de Anthropic: tu pregunta y un contexto del día que puede incluir **títulos de tareas, títulos y horarios de citas, títulos de tareas atrasadas, métricas de productividad y montos de gastos por categoría**. Si tu pregunta trata de tu empresa y tienes sesión de Oráculo, el texto de la pregunta puede enviarse también a nuestro servidor para recuperar contexto de la empresa. No uses Pythia si no quieres que estos datos salgan del dispositivo.

### 6. Lo que NO hacemos
- Sin publicidad, sin identificadores publicitarios (IDFA), sin rastreo entre apps o sitios.
- Sin SDKs de analytics ni de reporte de crashes de terceros.
- Sin venta ni intercambio de datos personales con data brokers.
- Sin cuentas obligatorias para usar la app.

### 7. Conservación y eliminación de datos
- Datos en el dispositivo e iCloud: elimínalos borrando contenido en la app, o quitando la app y sus datos de iCloud (Ajustes de iOS → Cuenta Apple → iCloud).
- Datos en el servidor de Oráculo (cuenta, métricas, títulos de juntas): solicita su eliminación al correo de contacto; eliminamos en un máximo de 30 días.
- Anthropic recibe las solicitudes de Pythia con tu propia clave; su conservación se rige por las políticas de Anthropic para tu cuenta.

### 8. Menores
La app es una herramienta de productividad para público general y no recopila datos de menores a sabiendas.

### 9. Cambios
Actualizaremos esta página y la fecha de vigencia cuando la política cambie. Los cambios relevantes se anunciarán en las notas de versión de la app.
