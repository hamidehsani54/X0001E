
# **DocuMeta AI**

This master’s thesis explores the application of Artificial Intelligence (AI) in the digitization of unstructured documents which contains normal text, handwritten text and also integers- and at the end extracting metadata from based on the pre-defined keywords. As digitization progresses, the efficiency in handling such documents remains a considerable challenge due to their unstructured nature and varied handwritten quality. The research evaluated several Optical Character Recognition (OCR) models, including Pytesseract, EasyOCR, KerasOCR, docTR, to identify the most effective method for converting handwritten documents into digital, searchable formats. By leveraging advanced AI technologies and extensive experiments, the study aims to enhance the accessibility and manageability of these documents while reducing the time and resources required for manual processing. The integration of metadata extraction significantly boosts the utility of digitized content, making it easier to organize, search, and retrieve information efficiently. 

# Models Used
* PyTesseract [npm worspace](https://pypi.org/project/pytesseract/)
* EasyOCR [npm worspace](https://github.com/JaidedAI/EasyOCR)
* docTR [npm worspace](https://github.com/mindee/doctr)
* KerasOCR [npm worspace](https://github.com/faustomorales/keras-ocr)

Do you want to test it?
Download any model you want and upload it on your google colab directory or copy past the code in your google colab file and run it. 


# Running time based on different device 
| Model         | Device        | Total Processing time (sec) |
| ------------- |:-------------:| ---------------------------:|
| Pytesseract   | CPU           | 24.185                      |
| EasyOCR       | CPU           | 171.275                     |
| docTR         | CPU           | 64.741                      |
| KerasOCR      | CPU           | 309.529                     |
| Pytesseract   | A100 GPU      | 6.259                       |
| EasyOCR       | A100 GPU      | 15.137                      |
| docTR         | A100 GPU      | 27.403                      |
| KerasOCR      | A100 GPU      | 24.213                      |
