# Elliot Web Frontend

A modern web interface for the Elliot recommendation framework, featuring data preprocessing, model training, and evaluation capabilities.

## Overview

Elliot Web is a React-based web application that provides an intuitive interface for interacting with the Elliot recommendation framework. The application consists of three main components:

- **Data Preprocessing**: Configure and prepare your recommendation datasets
- **Recommendation**: Train one or more recommendation models
- **Evaluation**: Set up evaluation configurations and metrics

## Technologies Used

- **Frontend Framework**: React
- **UI Components**: Material-UI (MUI)
- **State Management**: React Hooks (useState, useEffect)
- **Styling**: CSS with MUI's styling solutions
- **Navigation**: React Router
- **Notifications**: Notistack

## Features

### Data Preprocessing
- Three loading strategies: Dataset, Fixed, and Hierarchy
- Eight pre-filtering approaches
- Multiple splitting strategies
- Client-side validation
- Progress tracking with animated progress bar

### Recommendation
- Dynamic model configuration
- Support for multiple recommendation models
- Parameter customization with default values
- Real-time validation
- Visual feedback during training

### Evaluation
- Comprehensive metrics selection
  - Simple metrics
  - Complex metrics
- Customizable cutoff values
- Statistical testing options
- Dynamic parameter validation

## Web Scraper

The project includes a web scraper built to extract model and metric information from Elliot's documentation.

### Scraper Features
- Extracts recommendation model details
- Captures evaluation metrics
- Organizes data into structured JSON format
- Supports automatic updates when documentation changes

### Technologies Used for Scraper
- Cheerio for HTML parsing
- Axios for HTTP requests
- Node.js fs module for file operations

