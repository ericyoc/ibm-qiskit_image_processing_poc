# Quantum Image Processing with Qiskit

This project demonstrates basic quantum image processing techniques using Qiskit, a quantum computing framework. It's based on the work from [ica574's quantum-image-processing repository](https://github.com/ica574/quantum-image-processing).

## Overview

This code implements a quantum image processing algorithm that:

1. Downloads and processes a test image
2. Encodes the image into a quantum circuit
3. Applies a Quantum Fourier Transform (QFT)
4. Visualizes the results

## Key Features

- Image to quantum state encoding
- Custom Quantum Fourier Transform implementation
- Bloch sphere visualization of quantum states
- Text-based quantum circuit visualization

## How It Works

1. **Image Processing**: 
   - Downloads a test image
   - Converts it to binary (black and white)
   - Flattens the image into a 1D array

2. **Quantum Encoding**:
   - Creates a quantum circuit where each qubit represents a pixel
   - Encodes the binary image data using basis encoding

3. **Quantum Fourier Transform**:
   - Applies a custom QFT to the encoded image circuit

4. **Visualization**:
   - Displays Bloch sphere representations before and after QFT
   - Prints a text representation of the final quantum circuit

## Purpose

This project serves as a demonstration of how classical image data can be encoded into quantum states and manipulated using quantum operations. It's primarily intended for educational purposes and as a starting point for more complex quantum image processing algorithms.

## Acknowledgments

This code is adapted from the work by ica574. For more detailed information and the original implementation, please visit the [original repository](https://github.com/ica574/quantum-image-processing).

## Disclaimer

This is a proof-of-concept implementation and not intended for processing large-scale images on current quantum hardware. It demonstrates the potential of quantum-classical hybrid approaches in image analysis.

## License
Copyright 2024 Eric Yocam

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
