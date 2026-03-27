# LoomCalc — Weaving Calculator

A simple, browser-based weaving calculator that helps you estimate yarn consumption and fabric costs.

[**Live Demo**](https://parin23.github.io/weaving-calc-utils/)

## What it does

LoomCalc calculates how much yarn you need per meter of fabric and estimates the total cost based on yarn rates.

## How to use

Simply open `index.html` in any web browser. No installation or server required.

## Features

- **Yarn consumption** — Calculate grams of yarn needed per meter of fabric
- **Cost estimation** — Enter yarn rates (₹/kg) to estimate total fabric cost
- **Pattern repeats** — See how many pattern repeats fit per meter
- **Multiple yarns** — Configure multiple yarns with different deniers, densities, and picks
- **Wastage allowance** — Add a percentage for waste/trimming
- **Metric/Imperial** — Input in inches, see metric conversions

## Input Reference

| Field | Description |
|-------|-------------|
| Fabric Width | Width of your fabric in inches |
| Wastage % | Extra yarn for waste/trimming (default: 8%) |
| Denier | Yarn thickness (higher = thicker) |
| Rate (₹/kg) | Cost per kilogram of yarn |
| Density (ppi) | Picks per inch |
| Picks per repeat | Number of picks in one pattern repeat |

## Tech

Single HTML file with vanilla JavaScript. No dependencies, no build step.
