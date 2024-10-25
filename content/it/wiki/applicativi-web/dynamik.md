---
title: "Dynamik"
date: 2023-10-06T10:58:08+02:00
---

## Introduzione

[Dynamik](https://github.com/cartabinaria/dynamik) è l'applicativo web che ti
permette di consultare le raccolte di risorse di CartaBinaria.

## Sviluppo

Clona il progetto, installa le dipendenze e aggiorna i sottomuduli Git:

```bash
pnpm install
git submodule init
git submodule update
```

Crea un file `.env` con
```env
VITE_UPLD_URL="http://localhost"
```

Per avviare un'istanza di sviluppo:

```bash
pnpm dev
```

## Compilazione

Per compilare un'istanza di produzione:

```bash
pnpm build
```

Per vederne un'anteprima:

```bash
pnpm preview
```

## Istanze pubbliche

Al momento, manuteniamo solo un'[istanza pubblica di
Dynamik](https://dynamik.vercel.app/). Essa è aggiornata automaticamente
ogniqualvolta `main` subisce modifiche.

----
## Link utili

[📊Build Status](https://dynamik.vercel.app/build)
