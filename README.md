# PDF Extraction and Text Categorization Project

This project demonstrates how to extract text from a PDF file and categorize the text into predefined categories. The extracted and categorized text is then saved into a CSV file.

## Prerequisites

Make sure you have the following libraries installed:

- `fpdf` for generating PDF files
- `PyPDF2` for extracting text from PDF files
- `pandas` for handling data and saving it to CSV

## Working of the Project
This project demonstrates the process of extracting text from a PDF file, categorizing the extracted text based on predefined categories, and saving the categorized text into a CSV file. The workflow involves three main steps:

PDF Generation: A sample PDF file is generated with sections for Introduction, Methods, Results, Discussion, and Conclusion using the fpdf library. Each section contains relevant text to simulate a structured document.

Text Extraction and Categorization: The PyPDF2 library is used to read and extract text from each page of the generated PDF. The extracted text is then categorized based on keywords that match the predefined sections. This categorization helps in organizing the content based on its context.

Saving to CSV: The categorized text is compiled into a pandas DataFrame and saved into a CSV file. This CSV file contains two columns: 'Category' and 'Text', which store the section name and the corresponding extracted text, respectively.

By following these steps, the project efficiently demonstrates how to handle PDF text extraction and categorization, making it useful for various text analysis and document processing tasks.









## Output
PDF File: A sample PDF file (sample.pdf) with sections for Introduction, Methods, Results, Discussion, and Conclusion.
CSV File: A CSV file (categorized_text.csv) containing the extracted and categorized text from the PDF.
## Example Output
sample.pdf
categorized_text.csv

## Deployment
Successfully deployed the model in Huggingface at the url(https://huggingface.co/spaces/rushi-k/App_7)
## License
This project is licensed under the MIT License.
