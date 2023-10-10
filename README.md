# Malaria Detector

![Malaria Detector](malaria_image.jpg)

This project is a Malaria Detector implemented in MATLAB. It processes microscope images to identify malaria parasites using basic image processing techniques. If the total area of detected regions exceeds a certain threshold, it indicates the presence of malaria.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Project Structure](#projectstructures)
- [Usage](#usage)

## Overview

Malaria is a prevalent and deadly disease in many parts of the world. Timely detection and diagnosis are crucial for effective treatment. This project offers a basic tool to help detect potential malaria-infected areas in microscope images.

## Prerequisites

Before using this Malaria Detector, ensure that you have the following requirements:

- MATLAB installed (tested with MATLAB R20XX or later)
- Image Processing Toolbox (if not included with your MATLAB distribution)

## Project Structure

- Malaria Detector: The main project folder.
 - app.mlapp: MATLAB app file for the Malaria detection app.
  - MalariaDetector.app: MATLAB app bundle file for the Malaria detection app.
   - test_images: Folder containing test images for malaria detection.
      - infected: Subfolder containing infected image samples.
      - NotInfected: Subfolder containing non-infected image samples.


## Usage

1. Clone or download this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/malaria-detector.git
