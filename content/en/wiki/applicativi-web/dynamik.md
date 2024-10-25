---
title: "Dynamik"
date: 2023-10-06T10:58:08+02:00
---

## Introduction

[Dynamik](https://github.com/cartabinaria/dynamik) is the web application that allows you to browse the collections of resources of CartaBinaria.

## Development

Clone the project, install dependencies, and update Git submodules:

```bash
pnpm install
git submodule init
git submodule update
```

Create a `.env` file with:

```env
VITE_UPLD_URL="http://localhost"
```

To start a development instance:

```bash
pnpm dev
```

## Compilation

To compile a production instance:

```bash
pnpm build
```

To preview it:

```bash
pnpm preview
```

## Public Instances

For the time being, we are maintaining a single [public Dynamik
instance](https://dynamik.vercel.app/). Its depolyment is automatically
performed when the `main` branch is updated.

While the deployment of the second and third instances is controlled by CI/CD processes, for the first one, refer to [the guide on infrastructure automation](https://cartabinaria.github.io/wiki/infrastruttura/automazione/index.html).

----
## Useful Links

[📊Build Status](https://dynamik.vercel.app/build)
