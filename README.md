# Boost (Step-Up) Converter PCB

## Overview
This repository houses the schematic and layout files for a step-up (boost) power converter in KiCad. 

## Features
- Input: 2.5V DC nominal
- Output: 12 V @ 0.1–0.12 A target
- Test load: 240 Ω (≈50 mA @ 12 V)
- Topology: 2.5 V → 12 V boostDesign based on LT1302 2 V→12 V / 120 mA datasheet example

## Repository Structure
- `/schematic`: KiCad project schematic files.
- `/layout`: Board layout and 3D step models.
- `/manufacturing`: Gerber files, drill files, and Bill of Materials (BOM).
