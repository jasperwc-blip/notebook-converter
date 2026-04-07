[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jasperwc-blip/notebook-converter/blob/main/Notebook_Converter.py)
# Jupyter Notebook to PDF/HTML Converter (Colab Edition)

A streamlined, browser-based utility designed to run in Google Colab. This tool provides a graphical interface to convert your `.ipynb` files into high-fidelity PDFs or HTML files using the `nbconvert` WebPDF engine.

## Features
* **No Local Setup:** Runs entirely in the cloud via Google Colab.
* **Format Preservation:** Uses the native WebPDF engine to preserve JupyterLab and Classic visual styles perfectly.
* **Isolated Workspace:** Automatically creates and cleans a temporary workspace for every conversion to prevent file conflicts.
* **Easy Download:** Automatically triggers a browser download of your converted file.

## How to Use
1.  **Upload to Colab:** Upload the `Notebook_Converter.py` (or the `.ipynb` version) to your Google Colab instance.
2.  **Run the Cell:** Execute the code cell to generate the conversion interface.
3.  **Upload & Select:** * Click **Upload File** to select a notebook from your computer.
    * Choose your format (HTML, JupyterLab PDF, or Classic PDF).
4.  **Convert:** Click **Convert Now**. The tool will install necessary dependencies in the background and download your file once finished.

## Requirements
The script automatically handles installations within the Colab environment, including:
* `nbconvert[webpdf]`
* `playwright` (Chromium)
