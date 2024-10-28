# WaveCalc
This repository contains an Excel-based Wave Calculator designed to calculate wave characteristics using the **Airy (linear) wave theory**. Developed initially as a spreadsheet to simplify wave parameter calculations, it has been updated for improved usability. This tool can be applied in coastal and ocean engineering to analyze various wave properties, including wave length, wave celerity, wave breaking parameters, and wave height changes with depth.

![Wave Calculator Screenshot](https://github.com/sradfar/WaveCalc/blob/main/WaveCalc.jfif)

## Features

- **Wave Parameter Calculation**:
  - Calculates wave length using the **Newton Raphson method**.
  - Computes wave celerity, group velocity, and relative depth.
  - Provides a categorization of the wave zone based on depth.

- **Wave Height Adjustments**:
  - Calculates wave height after it propagates to a different water depth.
  - Includes shoaling and refraction effects for accurate wave height estimation in new depth zones.

- **Wave Breaking Analysis**:
  - Determines breaking index, wave height at breaking, and other critical parameters for wave breaking.
  - Analyzes surf similarity and splitting indices to characterize breaking conditions.

## Input Parameters

The calculator requires the following inputs:
- Wave height (\( H \))
- Wave period (\( T \))
- Water depth (\( d \))
- Gravitational acceleration (\( g \))
- Water density (\( \rho \))
- Bed slope (\( \tan \alpha \))

## Output Parameters

The calculator provides the following outputs:
- **Wave Parameters**: Wave length, wave celerity, group velocity, and relative depth.
- **Wave Breaking Parameters**: Breaking index, wave height at breaking, depth at breaking, surf similarity, and splitting parameters.
- **Secondary Depth Calculations**: Wave height adjustments based on new depth, shoaling and refraction coefficients, and the adjusted wave angle.

## Usage

1. Download the **Wave Calculator Excel file** from this repository.
2. Open the file and input the necessary wave data under the "Input data" section.
3. The calculations will automatically update in the relevant sections for wave parameters, wave height at secondary depth, and wave breaking calculations.

## Methodology

The wave calculator utilizes **Airy wave theory** (small-amplitude wave theory) and the **Newton Raphson method** to iteratively solve for wave length. This approach is efficient for calculating wave properties in transitional and deep water zones.

## Color Coding

- **User Input**: Fields for manual data entry.
- **Automated Calculation**: Automatically populated based on input values.

## Developer

Developed by **Soheil Radfar**  
Email: [soheil.radfar92@gmail.com](mailto:soheil.radfar92@gmail.com)
