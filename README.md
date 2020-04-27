# PDF Form Filler

![PDF Filler](screenshots/methods.png "PDF Filler")

---

This repository contains the Python code to fill forms in PDF using two different methods. The code was taken from different sources and adapted to work according to my requirements.

## Method 1: Form Field Text Update

This method uses a pdf form with fields created in Adobe Acrobat DC or similar software and those fields are filled through Python code. The way I created the fields in the pdf file was through a free site online: [PDF Escape](https://www.pdfescape.com)

Source of base code: [Bostata](https://bostata.com/how-to-populate-fillable-pdfs-with-python/)

## Method 2: Text Overlay

This method uses an empty pdf file. The Python code creates a new layer with the text you want to map to the pdf file and it is finally overlayed to one layer.

Source of base code: [Blog Python Library](https://www.blog.pythonlibrary.org/2018/05/22/filling-pdf-forms-with-python/)
