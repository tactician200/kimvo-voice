<p align="center">
  <img src="assets/icon.png" width="128" alt="Kimvo Voice" />
</p>

<h1 align="center">Kimvo Voice</h1>

<p align="center"><strong>Dicta. Estructura. Ejecuta.</strong><br>
Dictado por voz para Mac: doble-tap en la tecla <kbd>⌘ derecha</kbd>, habla, y el texto aparece en tu cursor — en cualquier app.</p>

---

## Descargar

**[⬇ Última versión (.dmg)](../../releases/latest)** · macOS · Apple Silicon (M1 o superior) · **[🌐 Landing](https://tactician200.github.io/kimvo-voice/)**

> Beta privada gratuita. Necesitas una API key de Groq (gratis, se configura en el primer arranque).

## Instalar (2 minutos)

1. Abre el `.dmg` y arrastra **Kimvo Voice** a **Aplicaciones**.
2. **Primera apertura: clic derecho sobre la app → Abrir → Abrir.**
   Es un build de beta sin notarizar por Apple, así que macOS muestra un aviso la primera vez; con clic derecho lo autorizas y no vuelve a preguntar.
3. Sigue el asistente de primer arranque:
   - **API key de Groq** (obligatoria, gratis): créala en [console.groq.com/keys](https://console.groq.com/keys). La app la valida y la guarda en tu Keychain — nunca sale de tu Mac.
   - **Permisos**: Micrófono y Accesibilidad. La app te abre el panel correcto de Ajustes del Sistema; activa Kimvo Voice y listo.

## Usar

- **Doble-tap ⌘ derecha** → habla → doble-tap de nuevo para terminar → el texto se pega donde esté tu cursor.
- Desde el ícono en la barra de menú eliges el modo de procesamiento:

| Modo | Qué hace |
|---|---|
| **Dictar** | Transcripción tal cual, al cursor |
| **Organizar** | Limpia muletillas y ordena lo dictado, sin cambiar el sentido |
| **Optimizar** | Convierte lo dictado en un prompt estructurado para Claude/ChatGPT/Cursor |
| **Resumir** | La esencia en 2-3 frases |
| **Explicar** | Explicación del texto, en voz o pegada |

## Qué hay debajo

- **Whisper Large v3 vía Groq** — transcripción cloud en menos de un segundo, muy buena en español.
- **Fix AirPods** — si hay un micro Bluetooth por defecto, la app usa el micro interno del Mac (el perfil Bluetooth degrada la calidad de dictado).
- **HUD en pantalla** — cápsula flotante con estado de grabación y botón de stop.
- **Tu key, tu Keychain** — el audio va a Groq solo para transcribirse, con tu propia key; nada pasa por servidores nuestros.

## Requisitos

- Mac con **Apple Silicon** (M1/M2/M3/M4). No corre en Macs Intel.
- Probada en macOS 26 (Tahoe); debería funcionar en Sequoia (15).
- Conexión a internet (la transcripción es cloud en esta beta).

## Feedback

Eres parte de una beta chica, así que todo comentario sirve:

- **Desde la app**: menú de la barra → **"Enviar feedback…"** (llega directo al desarrollador).
- O abre un [Issue](../../issues) en este repo.

---

<sub>Kimvo Voice está en beta privada. Este repositorio publica los builds; el código fuente no es público por ahora.</sub>
