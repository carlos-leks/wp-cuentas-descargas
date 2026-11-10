# WP Cuentas

App de macOS para tener **WhatsApp Web con varios números a la vez** en una sola ventana, y cambiar de uno a otro al momento. También puede enseñar los chats de todos los números juntos en una sola lista.

No es una app de WhatsApp ni de Meta: es WhatsApp Web dentro de una ventana.

## Descargar
En [Releases](../../releases/latest), el `.zip` de la última versión. Descomprímelo y arrastra **WP Cuentas** a **Aplicaciones**.

## La primera vez
macOS la bloquea porque no viene de la App Store. Abre Terminal y pega:

```
xattr -dr com.apple.quarantine "/Applications/WP Cuentas.app"
```

O bien: ábrela, pulsa «OK» en el aviso, y en Ajustes del Sistema → Privacidad y seguridad pulsa «Abrir igualmente».

## Usarla
- **＋** (o ⌘N): añade un número con un nombre, por ejemplo «Personal».
- Sale un código QR: en el móvil de ese número, WhatsApp → Ajustes → **Dispositivos vinculados** → Vincular un dispositivo. Una sola vez por número.
- Cambia de número con los nombres de la barra de arriba o con ⌘1, ⌘2…
- Tres vistas: un número cada vez, todos a la vez (⌘D) y todos los chats juntos en una lista (⌘J).
- Los mensajes nuevos salen en un aviso arriba a la derecha.
- Ajustes: ⌘,.

## Actualizaciones
La app mira aquí al abrirse y, si hay una versión nueva, ofrece instalarla sola. Los números siguen vinculados.

Necesita macOS 14 (Sonoma) o posterior. Funciona en Macs con chip de Apple e Intel.
