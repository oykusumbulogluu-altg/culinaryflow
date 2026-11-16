# culinaryFLOW — Patisserie Workshop

A buildless, English-language bakery management prototype. Serve the repository root using a static HTTP server; no compilation is required.

## Features

- Twelve pastry recipes with batch-scaled ingredient lists, yields, target timings and allergens.
- Five-step photographic training guides for every recipe, with checkpoints, common mistakes and device-local reading progress.
- Stock lots, goods receiving, suppliers, shelf locations, use-by dates, minimum levels, stock counts and shopping-list export.
- Ingredient reservations for planned batches and earliest-expiry-first consumption on completion.
- Four-stage production board, pause/resume timers and a completion checklist.
- Eight interactive kitchen areas linked to stock, receiving and production.

## Data and training limits

Records are saved in the current browser's local storage. Different visitors and devices do not share inventory or production records. Download the JSON records from the footer for a local backup. Publishing does not upload anyone's existing browser data.

Training process photos were generated with ImageGen and are labelled accordingly. They illustrate the recipe method and are not photographs of a real kitchen trial. The recipes and procedures require supervised kitchen validation. A reviewed guide records reading progress, not practical competence.

## Hosting

Live application: https://culinaryflow.shady2kk.chatgpt.site/

This repository contains the static application files at its root. Run `python3 -m http.server 8000` in this folder, then open http://localhost:8000. No build step is required.
