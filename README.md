# PAC-Extractor

PAC-Extractor is a simple Python script that extracts all necessary files from a `.pac` file used in firmware packaging. This tool is useful for unpacking and analyzing Spreadtrum/Unisoc firmware PAC files.

## Features

- Extracts all files from a `.pac` firmware package
- Optional cleanup of temporary files
- Displays extracted content structure
- Custom output directory support

## Clone the Repository

```bash
git clone https://github.com/bismoy-bot/PAC-Extractor
```
```bash
cd PAC-Extractor
```

Usage

Run the script using:
```bash
python3 extractor.py [-h] [-d] [-c] pacfile [outdir]
```
Arguments

pacfile (required): The input .pac firmware file to be extracted.

outdir (optional): Directory where the extracted files will be saved. If not specified, a folder with the PAC file name will be created.


Optional Flags

-h, --help: Show help message and exit.


Example:

python3 extractor.py firmware.pac output_folder



Requirements:

Python 3.x


No additional libraries are required as the script uses built-in Python modules.

License

This project is licensed under the MIT License.


---

Developed by Bismoy Ghosh.
