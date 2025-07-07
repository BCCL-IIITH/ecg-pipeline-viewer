# ECG Pipeline Results Viewer

An interactive web application for visualizing ECG signal processing pipeline results.

## Features

- Step-by-step visualization of ECG processing pipeline
- Interactive image zoom functionality
- Responsive design for mobile and desktop
- Support for multiple PDF processing results

## Live Demo

Visit the live demo: [https://yourusername.github.io/ecg-pipeline-viewer/](https://bccl-iiith.github.io/ecg-pipeline-viewer/)

## Project Structure

- `index.html` - Main application file
- `PDF/` - Contains processing results for each PDF
  - `1/steps/` - Step-by-step images for PDF 1
  - `2/steps/` - Step-by-step images for PDF 2
  - `3/steps/` - Step-by-step images for PDF 3
  - `4/steps/` - Step-by-step images for PDF 4

## Pipeline Steps

1. Original ECG Image
2. Gridline Removal
3. Peak Detection
4. ROI Detection
5. Signal Extraction
6. Filtered Signals
7. Signal Segmentation
8. Signals on Original Image
9. Normalized Signals
10. Lead II Extended
