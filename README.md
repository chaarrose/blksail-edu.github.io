# BLKSAIL AUVC Course Site

This repository contains the documentation and announcement site for the MIT Beaver Works Summer Institute Autonomous Underwater Vehicle Challenge (AUVC), maintained by BLKSAIL.

The site includes:
- the current course materials
- archived versioned course content for prior years
- program announcements published through the blog

## Stack

- Docusaurus 3
- React 19
- Yarn 4
- Node 22

## Install

```bash
corepack enable
yarn install
```

## Local Development

```bash
yarn start
```

This starts the local Docusaurus dev server with live reload.

## Build

```bash
yarn build
```

The production site is generated into `build/`.

## Type Check

```bash
yarn typecheck
```

## Content Layout

- `docs/`: current course content
- `versioned_docs/`: archived yearly course material
- `blog/`: announcements and updates
- `static/`: static assets served as-is
