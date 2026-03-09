# Excavator Web

A WebGL runtime for viewing an optimized excavator game mesh derived from a STEP CAD file. This project demonstrates the technical artistry of converting complex CAD geometry into an efficient, web-optimized 3D mesh.

## Overview

This is a mesh visualization tool showcasing the conversion pipeline from professional CAD (STEP format) to an optimized game-ready mesh. The excavator model has been processed for polygon optimization to run efficiently on the WebGL platform.

**View the finalized game asset model**: [Unity Web Viewer](https://abxdnego.github.io/excavator-web/)

## Technical Achievement

- **CAD Processing**: STEP file processing using Pixyz Studio for polygon extraction and optimization
- **Mesh Optimization**: Polygon reduction while maintaining visual fidelity
- **WebGL Export**: Unity WebGL build for browser deployment to showcase scalability

## Use Case
This viewer demonstrates equipment familiarization training - allowing operators to inspect heavy machinery from all angles before physical interaction. The orbital camera provides 360° visibility for comprehensive equipment understanding.

## Technical Stack
- **CAD Source**: STEP file format
- **Processing**: Pixyz Studio for CAD conversion and polygon optimization, DCC tools for mesh cleanup and export preparation
- **Engine**: Unity with WebGL export
- **Deployment**: GitHub Pages
