# PDFGuard: Secure and Sanitize PDFs with Python

PDFGuard is a user-friendly Python application designed to enhance the security of PDF files by removing potential security threats and hidden content. It achieves this by converting PDF pages into images and then creating new, sanitized PDFs from these images.

## Getting Started

### Prerequisites

Before using PDFGuard, make sure you have the following prerequisites installed on your computer:

- **Python:** If you don't have Python installed, download it from the [official website](https://www.python.org/downloads/).

### Installation

Follow these steps to install and run PDFGuard:

1. **Download the Code:**
   - Click the "Code" button at the top of this GitHub page.
   - Select "Download ZIP" to download the code as a ZIP archive.
   - Extract the contents of the ZIP archive to a folder on your computer.

2. **Install Dependencies:**
   - Open your system's command prompt or terminal and navigate to the folder where you extracted the code.
   - Run the following command to install the required Python libraries:
     ```shell
     pip install PyMuPDF img2pdf
     ```

3. **Run the Application:**
   - After installing the dependencies, open the command prompt or terminal, navigate to the code folder.
   - Then run the following command:
     ```shell
     python PDFGuard.py
     ```

## How to Use

PDFGuard provides an easy-to-use graphical user interface (GUI). Follow these steps to sanitize your PDF files:

### 1. Select Input PDF Files

- Click the "Browse" button next to "Input PDF Files."
- A file selection dialog will open.
- Navigate to the PDF files you want to sanitize, select them, and click "Open."

### 2. Choose Output Folder

- Click the "Browse" button next to "Output Folder."
- Select the folder where you want to save the sanitized PDFs and click "Open."

### 3. Sanitize PDF

- Click the "Sanitize PDF" button to start the sanitization process.
- The application will convert the input PDFs into images, create sanitized PDFs, and save them in the specified output folder.

## Important Information

- PDFGuard is designed to enhance the security of PDF files by removing potential security threats and hidden content. However, it may not guarantee complete security for all types of PDFs.
- The output PDFs may not retain the same quality and text selectability as the input PDFs.
- If you require additional security measures for your PDFs, you should explore other tools and methods.
