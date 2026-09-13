# ngebolang-system

NGEBOLANG — WebGIS trip planner multi-moda Yogyakarta. Repo ini menggabungkan frontend dan backend sebagai git submodule.

## Struktur

- [`frontend/`](https://github.com/AnthonyS051105/ngebolang-mapid) — Next.js frontend + backend ringan Next.js
- [`backend/`](https://github.com/AnthonyS051105/ngebolang-mapid-backend) — Backend Python (routing, chat, laporan warga, dsb.)

## Live Deploy

- Frontend: https://ngebolang-mapid.vercel.app/
- Backend: https://ngebolang-mapid-backend-production.up.railway.app

## Clone dengan submodule

```bash
git clone --recurse-submodules https://github.com/AnthonyS051105/ngebolang-system.git
```

Kalau sudah terlanjur clone tanpa `--recurse-submodules`:

```bash
git submodule update --init --recursive
```
