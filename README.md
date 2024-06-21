# CR2 to JPEG Converter

## Overview

CR2 to JPEG Converter is a standalone executable application that converts Canon CR2 RAW files to high-quality JPEG files. This tool is designed to be user-friendly and efficient, allowing users to batch process multiple CR2 files with a specified output quality.

## Features

- Batch conversion of CR2 files to JPEG.
- Adjustable JPEG output quality.
- Simple double-click execution.

## Usage

1. **Download the Executable:**
   Download the `cr2_to_jpeg_converter.exe` from the [releases](https://github.com/ahmetaraci/cr2tojpeg/releases) page.

2. **Run the Application:**
   Simply double-click the `cr2_to_jpeg_converter.exe` to start the application.

3. **Input and Output Directories:**
   Follow the on-screen prompts to select the directory containing the CR2 files and the output directory where the converted JPEG files will be saved.

4. **Set JPEG Quality:**
   Specify the desired quality for the output JPEG files (1-100), where 100 represents the highest quality.

## Example

1. Double-click `cr2_to_jpeg_converter.exe`.
2. Select the input folder containing your CR2 files.
3. Select the output folder where you want to save the JPEG files.
4. Enter the quality level for the JPEG files (e.g., 85).
5. Click "Convert" and wait for the process to complete.

## Development

This application was developed using Python and the Pillow library, then packaged into an executable using PyInstaller. The development process involved:

1. Writing the conversion script with Pillow.
2. Testing the script to ensure accurate CR2 to JPEG conversion.
3. Packaging the script into a standalone executable using PyInstaller.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please contact [muhammetahmet.araci@gmail.com].

[Visit Me & Contact ME](https://ahmetaraci.github.io)
