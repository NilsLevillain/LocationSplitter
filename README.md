
# LocationSplitter

## Introduction
LocationSplitter is a specialized tool designed to streamline the data ingestion process for Manhattan Active WMS 'Storage Location' data loaders. It simplifies the task of splitting an original file into multiple smaller files, each containing up to 500 lines, specifically for the 'Location' and 'LocationUom' tabs.

## Features
- **Efficiency**: Automates the splitting of large data files, reducing manual labor significantly.
- **Time-Saving**: Cuts down hours of work during various project phases, enhancing productivity.
- **Error Reduction**: Minimizes the risk of human error associated with manual file splitting.
- **Simplicity**: User-friendly interface that requires minimal training or technical knowledge.

On this note, a proper GUI has been developed in another version with PySimpleGUI allowing to select the input file, the ouput folder and modifying the max_lines parameter. This version allowed the portability of the project because no installation is required : neither Python nor any of its packages. However, as it is a '.exe' file, anti-malware softwares have a hard time letting the executable run. In another version I also wanted to generalize the tool and not only focus on the 'Location' data loaders, but any data loader. Contact me if you want the code I wrote for these upgrades.

## How It Works
The tool takes a single large file as input and divides it into manageable chunks. These smaller files are then ready to be ingested by the Manhattan Active WMS system, facilitating a smoother and faster implementation process.

## Usage
1. Clone the repository to your local machine.
2. Place the original 'Storage Location' file in the designated input directory and modify the 'Exemple.env' file.
3. Run the tool to generate the split files.
4. Use the output files for data ingestion in Manhattan Active WMS in the 'Storage Location' UI, via the 'Import data loader' feature.

## Requirements
- Python 3.x
- Manhattan Active WMS system access (for data ingestion)

## Installation
To get started with LocationSplitter, follow these steps:

git clone https://github.com/NilsLevillain/LocationSplitter.git cd LocationSplitter

## Contribution
Contributions to enhance LocationSplitter are welcome. Please feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is licensed under the GNU Affero General Public License v3.0 - see the LICENSE.md file for details.

## Acknowledgments
A big thank you to everyone involved in the development and testing of this tool, making the data ingestion process for Manhattan Active WMS more efficient.

---

For any further questions or feedback, please open an issue in the repository or submit a pull request with your suggestions.
