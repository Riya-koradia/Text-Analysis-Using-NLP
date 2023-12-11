# Text-Analysis-Using-NLP

1. Introduction:-
This Python script is designed for performing sentiment analysis and readability analysis on financial texts extracted from given URLs.

2. Dependencies:-
Make sure you have the following dependencies installed:
- pandas
- requests
- beautifulsoup4
- textblob
- nltk

3. Install the required dependencies using the following command:
-pip install pandas requests beautifulsoup4 textblob nltk

4. Instructions:-

1) Data Extraction
- The input data is provided in the file Input.xlsx.
- For each article in Input.xlsx, the script extracts the article text using Python and libraries such as BeautifulSoup.

2) Sentimental Analysis
- The script performs sentiment analysis on the extracted text.
- Cleaning is done using stop words lists from the StopWords folder.
- A master dictionary from the MasterDictionary folder is used to create dictionaries of positive and negative words.
- Derived variables such as Positive Score, Negative Score, Polarity Score, and Subjectivity Score are calculated.

3) Analysis of Readability
- Readability analysis is performed using the Gunning Fox index formula.
- Variables like Average Sentence Length, Percentage of Complex Words, Fog Index, and others are calculated.

4) Variables
- The output variables are defined in the "Text Analysis.docx" file.
- Look for these variables in the analysis document.

5) Output
- The output is saved in the format specified in the "Output Data Structure.xlsx" file.
- The script generates an Excel file named "Output_Data_Structure.xlsx" containing the computed variables.

