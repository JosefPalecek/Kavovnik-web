# Kávovník — e‑shop s administrací (v2)

**Datum sestavení:** 2026-02-16

- Přidán hero s fotografií, tematické fotky káv na produktových kartách, dekorativní prvky.
- Opraven přístup do **admin** (fallback bez ES modulů, polyfill `structuredClone`, robustnější `sessionStorage`).
- Admin funguje i při otevření přes `file://` v prohlížeči.

## Přihlášení do adminu
`admin` / `admin123`

## Spuštění
1. Rozbal ZIP a otevři `index.html`.
2. Katalog: `kavy.html`.
3. Admin: `admin.html` (funguje s ES Modules i bez — přes `<script nomodule>` fallback).

## Poznámka k fotkám
Fotky jsou načítány z Unsplash (bez nutnosti ukládat soubory). Kredity: Unsplash autoři (Coffee themed) — licence zdarma pro komerční i nekomerční použití.

## Produkční doporučení
Viz README v předchozí verzi; rád připravím i Node.js backend skeleton na přání.
