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
7z x filename.7z.001
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

## Additional Tips

- Always keep the original archive files until you verify the extracted contents
- Check the available disk space before extraction
- Make sure you have the necessary permissions for the destination folder
- Some archives may be password-protected; make sure you have the correct password

## Key Features
### Feature 1
Description and usage examples of the feature
![Feature 1 Screenshot](image_path)

### Feature 2
Description and usage examples of the feature
![Feature 2 Screenshot](image_path)

## User Guide
### Basic Workflow
1. Starting the Program
2. Import structure information by drawing, searching or loading external file.
3. Predict toxity
4. Saving and Exporting


### Interface Overview
#### Main Window
![Main Window](image_path)



### Advanced Features
#### Feature A
Detailed explanation of advanced feature A
```python
# Example code or configuration
setting_a = value_1
setting_b = value_2
```

#### Feature B
Detailed explanation of advanced feature B
![Feature B Advanced Usage](image_path)

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
