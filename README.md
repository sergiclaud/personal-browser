# Personal Browser

A native web browser for macOS, built with SwiftUI and WebKit (WKWebView).

**[⬇ Download the latest version](../../releases/latest)** · macOS 14 or later · Apple silicon (M1 or later) · signed with Developer ID and notarized by Apple

## Features

- **Tabs, bookmarks, history and profiles**, each profile with its own separate website data.
- **pUbo, the built-in content blocker**: blocks ads and trackers with WebKit content rules, removes empty ad slots, rejects cookie banners automatically and skips YouTube ads. Its rule lists are open and update themselves from [sergiclaud/pubo-listas](https://github.com/sergiclaud/pubo-listas).
- **Security keys (WebAuthn)**: YubiKey and other FIDO2 keys through libfido2, which runs in a separate sandboxed XPC service with USB access only.
- **Privacy**: App Sandbox, optional fingerprinting protection, removal of tracking parameters from links, dangerous-site warnings and clearing data on quit.
- **Client certificates** for sites that need them (for example, Spanish government services).
- **Page translation** with a local LibreTranslate server, so text never leaves your Mac.
- **Downloads** with speed, resume and checksum verification.
- **Developer tools**: Web Inspector (⌥⌘I) and view source.
- The interface is in Spanish.

## Install

1. Download `Personal-Browser-<version>.zip` from [Releases](../../releases/latest).
2. Open the zip and drag **Personal Browser** to your Applications folder.
3. Optionally, set it as your default browser in System Settings → Desktop & Dock.

This repository only hosts the releases; the source code is private.

---

## En español

Navegador nativo para macOS hecho con SwiftUI y WebKit: pestañas, marcadores, historial y perfiles; **pUbo**, el bloqueador de anuncios y rastreadores integrado (listas abiertas en [sergiclaud/pubo-listas](https://github.com/sergiclaud/pubo-listas)); llaves de seguridad (YubiKey) con libfido2 en un servicio aislado; App Sandbox y protección anti-huella; certificados de cliente; traducción local con LibreTranslate; e Inspector web (⌥⌘I).

**Descarga** el zip de la [última versión](../../releases/latest), ábrelo y arrastra **Personal Browser** a Aplicaciones. Requiere macOS 14 o posterior y un Mac con chip de Apple (M1 o posterior). Está firmado con Developer ID y notarizado por Apple.
