# Weaving Utilities

A collection of browser-based weaving calculators.

**LoomCalc** — Weft Yarn Calculator

[**Live Demo**](https://parin23.github.io/weaving-calc-utils/)

## What it does

LoomCalc calculates how much weft yarn you need per meter of fabric and estimates the total cost based on yarn rates.

(More calculators coming soon.)

## How to use

Simply open `index.html` in any web browser. No installation or server required.

## Features

- **Weft yarn consumption** — Calculate grams of yarn needed per meter of fabric
- **Cost estimation** — Enter yarn rates (₹/kg) to estimate total fabric cost
- **Pattern repeats** — See how many pattern repeats fit per meter
- **Multiple weft yarns** — Configure multiple weft yarns (Weft 1, Weft 2, etc.) with different deniers, densities, and picks
- **Wastage allowance** — Add a percentage for waste/trimming
- **Metric/Imperial** — Input in inches, see metric conversions

## Input Reference

| Field | Description |
|-------|-------------|
| Fabric Width | Width of your fabric in inches |
| Wastage % | Extra yarn for waste/trimming (default: 8%) |
| Denier | Weft yarn thickness (higher = thicker) |
| Rate (₹/kg) | Cost per kilogram of weft yarn |
| Density (ppi) | Picks per inch |
| Picks per repeat | Number of picks in one pattern repeat |

## Tech

Single HTML file with vanilla JavaScript. No dependencies, no build step.
