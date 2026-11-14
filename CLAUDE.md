# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Small educational games in plain HTML for 5th grade (Primaria). No build step, no server, no dependencies: each game is a single self-contained `index.html`.

| Path | Game |
|---|---|
| `index.html` | Landing page linking to the games |
| `mapas/index.html` | Explorador del Mundo (continents and oceans; America is a single continent) |
| `celulas/index.html` | Laboratorio de Células (animal and plant eukaryotic cell) |

Published with GitHub Pages from `main` (root folder): https://victorlopez.eu/juegos-primaria/

## Conventions

- Game text is in Spanish (castellano); code and identifiers in English.
- Keep each game in a single `index.html`; open it directly in the browser to test.
- Progress is stored in `localStorage` per game. Don't send data to any server.

## Git workflow

- The main branch is `main`.
- After **every change**, commit and push straight to `main`, without asking again.
