# FIFA 22 Player Stats Dashboard

This project provides a GUI-based data visualization tool built with Tkinter and Matplotlib to explore player statistics from the FIFA 22 dataset. Users can interactively select features and visualize data distributions through histograms and bar plots.

## Features

- **GUI interface** using `tkinter`
- Interactive **plotting** with `matplotlib`
- Basic **data preprocessing** and filtering of relevant features
- Support for **player-wise comparison** based on selected attributes
- Clean and minimal dashboard design

## Dataset

- **Source**: FIFA 22 Player Dataset (CSV format: `players_22.csv`)
- **Attributes Used**: Filtered down from over 100+ columns to core performance indicators (e.g., passing, dribbling, defending)

## Requirements

Install the required Python libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn pillow
