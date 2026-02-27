streamlit==1.38.0
langchain-community==0.2.16
langchain-text-splitters==0.2.4
langchain-chroma==0.1.3
langchain-huggingface==0.0.3
langchain-groq==0.1.9
unstructured==0.15.0
unstructured[pdf]==0.15.0
nltk==3.8.1
transformers
sentence-transformers


🔧 Step 1: Download Poppler for Windows
Go to: https://github.com/oschwartz10612/poppler-windows/releases

Download the latest poppler-xx_xx_xx.zip under Assets.

Extract the .zip file to a folder (e.g., C:\poppler).

🔧 Step 2: Add Poppler to your System PATH
Press Win + S, search for Environment Variables, and open it.

Click Environment Variables...

Under System variables, find and select Path, then click Edit...

Click New, and add the bin directory of your extracted folder (e.g., C:\poppler\bin)

Click OK on all dialogs to apply.

🔁 Step 3: Restart Terminal/IDE
Make sure to restart your terminal or IDE (e.g., VSCode) after making changes so the PATH updates.



Step 1: Install Tesseract
You need to manually install Tesseract OCR for your operating system:

🔹 Windows:

Download the installer from https://github.com/tesseract-ocr/tesseract (click "Releases").
Or use a direct link like: https://digi.bib.uni-mannheim.de/tesseract/

Install it (default path is usually C:\Program Files\Tesseract-OCR)

Step 2: Add Tesseract to your PATH
After installing, ensure the executable is accessible:

Open System Properties > Environment Variables

Under System Variables, find the Path variable → click Edit

Add the path to the folder where tesseract.exe is installed,
