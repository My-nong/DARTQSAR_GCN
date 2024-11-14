# DARTQSAR_GCN
Code for "Attention- and gate-augmented Graph Convolution Network modeling to predict the potential for Reproductive and Developmental toxicity"

# DART_Predictor
> Standalone software to deploy model based on "Attention- and gate-augmented Graph Convolution Network modeling to predict the potential for Reproductive and Developmental toxicity"

## Table of Contents
1. [Overview](#overview)
2. [System Requirements](#system-requirements)
3. [Installation](#installation)
4. [Key Features](#key-features)
5. [User Guide](#user-guide)
6. [FAQ](#faq)
7. [Version History](#version-history)

## Overview
Use this software, you can use model based on "Attention- and gate-augmented Graph Convolution Network modeling to predict the potential for Reproductive and Developmental toxicity" with structure information of specific molecule.

## System Requirements

### Minimum Requirements
- OS: Windows 10 or later / macOS 10.15 or later

### Recommended Requirements
- OS: Windows 11 / macOS 13 or later

## Installation

### Download
Download all parts (DART_Predictor_small.7z.001 through DART_Predictor_small.7z.016) from the repository.

### Guide to Extracting Split 7z Archives

#### Windows

##### Prerequisites
1. Install [7-Zip program](https://7-zip.org/)

##### Extraction Steps
1. Right-click on the `.7z.001` file
2. Select 7-Zip menu
3. Click "Extract Here"

#### macOS

##### Prerequisites
Install one of the following programs:
- Keka (App Store)
- The Unarchiver (App Store)

##### Extraction Steps
1. Double-click the `.7z.001` file
   - Or right-click → "Open With" → Select Keka/The Unarchiver

#### Unix/Linux

##### Prerequisites
Install p7zip:

###### Ubuntu/Debian
```bash
sudo apt-get install p7zip-full
```

#### CentOS/RHEL
```bash
sudo yum install p7zip p7zip-plugins
```

##### Extraction Steps
Run the following command in terminal:
```bash
7z x DART_Predictor_small.7z.001
```

#### Important Notes

- **Requirements:**
  - All split files (.7z.001, .7z.002, etc.) must be in the same folder
  - Filenames must be in correct sequential order
  - Verify that all files are completely downloaded
  - Only select the first file (.7z.001) to start extraction

- **Troubleshooting:**
  - If extraction fails, check for file corruption or missing parts
  - Verify the integrity of all split files
  - Make sure you have sufficient disk space for the extracted contents
  - If failed to extract, please contact as chltjs1921@naver.com.

## Additional Tips

- Always keep the original archive files until you verify the extracted contents
- Check the available disk space before extraction
- Make sure you have the necessary permissions for the destination folder
- Some archives may be password-protected; make sure you have the correct password

## Key Features
### Feature 1
Variety of input methods
  - Enter SMILES directly
  ![Feature 1 Screenshot]('Feature_1_direct.png')
  - Draw
  ![Feature 1 Screenshot]('Feature_1_draw.png')
  - Search
  ![Feature 1 Screenshot]('Feature_1_search.png')
  - Load external file
  ![Feature 1 Screenshot]('Feature_1_load.png')

### Feature 2
Not only prediction, but also visualization of molecular structure with subgraph
![Feature 2 Screenshot]('Feature_2.png')

### Feature 3
Save and export results by html and pdf format
![Feature 3 Screenshot]('Feature_3.png')

## User Guide
### Basic Workflow
1. Start the Program double-click DART_Predictor.exe
2. Import structure information by enter SMILES directly in the text box below, drawing structure in the canvas and click Get SMILES button to get SMILES, searching by PubChem CID or name at the search box next to the Search button with Search button, or loading external file(*.smi, *.mol, *.sdf files.) using Load button.
3. Predict toxity use Predict button below.
4. Saving and Exporting with html or pdf format. Also, you can initialize the result of prediction in the main window use Clear All button.


### Interface Overview
#### Main Window
![Main Window]('Main_window.png')


## FAQ
If you want FAQ, please contact as chltjs1921@naver.com. Also as troubleshooting.

## Version History

### v1.0.0 (Novenber 15, 2024)
- Initial release

---
## Support & Contact
- Email: minong960@sogang.ac.kr, chltjs1921@naver.com
- Website: https://hanbinoh.sogang.ac.kr/hanbinoh/

## License
This program is distributed under the MIT License.

### Additional Resources
- Paper:
