# Status Tool - Progress Dashboard

A standalone HTML tool for visualizing project progress using pie charts. Track data collection, validation, and other metrics across multiple categories.

## Features

- **Multiple Tables**: Create separate tracking tables (e.g., DNO, MNO)
- **Flexible Columns**: Add custom categories as columns
- **Two Row Types**:
  - **Pie Chart Rows**: Show progress with visual indicators
  - **Text Rows**: Display status text (Done, TBD, dates)
- **Progress Visualization**:
  - Amber: Last period progress
  - Green: Current period (if improved)
  - Red: Current period (if regressed)
- **Auto-Save**: Data persists in browser LocalStorage
- **Export/Import**: Backup and restore data as JSON

## Usage

1. Open `index.html` in any modern browser
2. Click **"+ Add Table"** to create a new tracking table
3. Add columns and rows as needed
4. Click on any cell to edit its values
5. Data saves automatically

## Pie Chart Legend

| Color | Meaning |
|-------|---------|
| Amber | Last period progress percentage |
| Green | Current period (positive progress) |
| Red | Current period (regression) |

## Data Persistence

- Data is saved automatically to browser LocalStorage
- Use **Export Data** to download a JSON backup
- Use **Import Data** to restore from a backup file

## Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required
