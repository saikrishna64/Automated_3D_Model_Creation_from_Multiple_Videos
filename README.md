<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automated 3D Model Creation from Multiple Videos</title>
</head>
<body>

# Automate Meshroom 3D Models Generation

This script automates the generation of 3D models using [Meshroom](https://alicevision.org/).

## Prerequisites

- Python 3.x
- Meshroom 2023.2.0 (Update the version if needed)

## Usage

1. **Select Input Folders:**
    - Click on the "Select Folders" button to choose one or more input image folders.
    - Use the "Remove Selected" button to remove any mistakenly selected folders.

2. **Select Output Folder:**
    - Click on the "Browse" button to choose the output folder where Meshroom results will be saved.

3. **Run Meshroom:**
    - Click on the "Run Meshroom" button to start the Meshroom processing.

## Script Execution

Ensure that you have set the correct path to your Meshroom executable in the script. The script performs the following steps:

- Camera initialization
- Feature extraction
- Image matching
- Feature matching
- Structure from Motion
- Dense scene preparation
- Depth map estimation
- Depth map filtering
- Mesh generation
- Mesh filtering
- Mesh decimation
- Mesh resampling
- Texturing

## Troubleshooting

If running the script as an executable doesn't produce the expected output, refer to the [troubleshooting guide](#troubleshooting) in the README.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</body>
</html>
