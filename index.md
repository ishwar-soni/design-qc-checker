# Design QC Checker

A Canva app that scans your designs for quality issues, accessibility problems, and inconsistencies.

## Features

- **Edge Proximity** — Detects elements too close to the edge that may get cut off when printed
- **Text Readability** — Flags text that is too small to read comfortably
- **Font Consistency** — Identifies designs using too many different fonts
- **Color Consistency** — Detects excessive color variation
- **Overlapping Elements** — Flags elements that significantly overlap each other
- **Image Resolution** — Detects images placed larger than their source resolution (may appear blurry)
- **Text Overflow** — Flags text that likely doesn't fit within its text box
- **Spacing Consistency** — Detects uneven gaps between elements that appear evenly spaced
- **WCAG Contrast** — Checks text contrast ratios for accessibility compliance
- **Alignment** — Finds elements that are slightly misaligned, including center-axis near-misses
- **Brand Palette** — Flags colors not in your defined brand palette

## Auto-Fix

One-click fixes for common issues:
- Edge proximity violations (repositions elements away from edges)
- Alignment snapping (snaps near-miss elements to median position)

## Export Report

Generate a QC report and copy it to your clipboard for sharing with clients or team members.

## Scan History

Track your scan results over time. View past scans, compare issue counts between scans, and drill into full issue details.

## Settings

- Toggle individual checks on/off
- Reorder how result groups appear
- Configure check thresholds (safe distances, font limits, contrast ratios, etc.)
- Dismiss and restore issues
- Define your brand color palette for enforcement

## Links

- [Privacy Policy](./privacy-policy)
- [Terms and Conditions](./terms)
- [Support (GitHub Issues)](https://github.com/ishwar-soni/design-qc-checker/issues)
