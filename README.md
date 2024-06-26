
# **HandText Detector AI**

This master’s thesis explores the application of Artificial Intelligence (AI) in the digitization of unstructured documents which contains normal text, handwritten text and also integers- and at the end extracting metadata from based on the pre-defined keywords. As digitization progresses, the efficiency in handling such documents remains a considerable challenge due to their unstructured nature and varied handwritten quality. The research evaluated several Optical Character Recognition (OCR) models, including Pytesseract, EasyOCR, KerasOCR, docTR, to identify the most effective method for converting the content of the file such us handwritten text, normal text and integers into digital, searchable formats. By leveraging advanced AI technologies and extensive experiments, the study aims to enhance the accessibility and manageability of these documents while reducing the time and resources required for manual processing. After that the file has been extracted to the XML file, I open the file and search for some pre-defined keywords and extract some metadata based on thesed keywords using a simple algorithm. 

# Models Used
*  [PyTesseract](https://pypi.org/project/pytesseract/)
*  [EasyOCR](https://github.com/JaidedAI/EasyOCR)
*  [docTR](https://github.com/mindee/doctr)
*  [KerasOCR](https://github.com/faustomorales/keras-ocr)

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
| docTR         | A100 GPU      | 21.288                      |
| KerasOCR      | A100 GPU      | 24.213                      |

# To run the code 
* Donwload the code
* Install Google Colab
* Upload the file/files in your Google Drive
* Upload the file that you want to convert it to machine readble fortmat
* Modify the file path
* Ready to go ✌️


