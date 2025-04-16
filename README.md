# Noel's Preswald Project

A data visualization application built with Preswald.

## Overview

This project uses Preswald to create interactive data visualizations. The application displays scatter plots and tables from sample CSV data.

## Features

- Interactive scatter plots using Plotly
- Data table visualization
- Custom branding and styling

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Preswald library

### Installation

1. Clone this repository
2. Install dependencies:
   ```
   pip install -e .
   ```

### Running the Application

Start the application with:

```
preswald run
```

The application will be available at `http://localhost:8501` by default.

## Project Structure

- `hello.py` - Main application entrypoint
- `data/` - Contains CSV data files
- `images/` - Contains logo and favicon
- `preswald.toml` - Configuration file for the Preswald application

## Configuration

The application is configured via `preswald.toml`, where you can modify:
- Project metadata
- Branding elements
- Data sources
- Logging settings 
