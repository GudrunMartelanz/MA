# README

This code repository is a part of the master's thesis titled "Optical Character Recognition und historische Ausstellungskataloge" for the Master of Arts (MA) degree at the University of Graz. The aim of the project was to examine and compare different OCR tools on the basis of historical exhibition catalogues.

**Title of Thesis:**  
Optical Character Recognition und historische Ausstellungskataloge (Optical Character Recognition and historical exhibition catalogues) 

**Subtitle:**  
Vergleich von Werkzeugen zur optischen Texterkennung anhand der Kataloge des Steiermärkischen Kunstvereins (Comparison of tools for optical text recognition using the catalogues of the Steiermärkischer Kunstverein)

**University:**  
University of Graz

**Author:**  
Gudrun Astrid MARTELANZ

**Supervisor:**  
Mag. Dr. phil. Martina Scholger

**Institution:**  
Department Centre for Information Modelling - Austrian Centre for Digital Humanities

**Year:**  
2024


---

## About the repository

This repository contains the used source material and the results as well as the script and documentations. The project is structured as follows:

## Main Directory Structure
```
.
├── catalogues
│   ├── catalogue 1
│   ├── catalogue 2
│   ├── catalogue 3
│   ├── catalogue 4
│   └── catalogue 5
├── doc
└── results
│   ├── OCR4all
│   ├── Tesseract-OCR
│   └── Transkribus
```
## Source Material
The source material for this project can be found in the catalogues folder. 

## Documentation
This project includes the following documentations:
1. `tesseract.txt` : Contains the used command-line commands in Tesseract OCR.
2. `ocr4all.docx` : Contains the used settings for the training models in OCR4all.

## How to Run
For [Tesseract] (https://github.com/tesseract-ocr/tesseract/tree/main) you will need Tesseract OCR and the required packages (including "deu.traineddata") installed. Tesseract requires command line usage. Please ensure that you copy the source material into the respective directory.
For [OCR4all] (https://www.ocr4all.org/guide/setup-guide/windows) you will need docker and the required OCR4all packages installed.
For [Transkribus] (https://www.transkribus.org/de) you will need to register on the respective platform.
## License 
The main part of the project is distributed under the CC-BY-4.0 License. The source material is distributed by Steiermärkische Landesbibliothek under CC BY-NC-SA AT 2018 www.landesbibliothek.steiermark.at. See each LICENSE.txt in the respective folder for more information.
