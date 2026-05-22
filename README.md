### EX9 Preprocessing on Twitter Data using Rapidminer

### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1137" height="451" alt="593065458-1552ec33-b80d-4bbe-b885-c01731f0113f" src="https://github.com/user-attachments/assets/7cd2ecb2-0d9d-4a74-9f92-1a1fd585386d" />

<img width="1119" height="429" alt="593065515-64af93c8-86f8-4f72-b6f7-2dc8bc4ec14a" src="https://github.com/user-attachments/assets/7c27adf4-316a-4098-9d0d-a0aaa6533743" />

<img width="1512" height="1074" alt="593065557-f17cd919-274a-48b3-aa9c-eea5f52a1aff" src="https://github.com/user-attachments/assets/36f3b938-ba60-47eb-a186-3d2422495acd" />

### Result:
Thus, the preprocessing technique on twitter data in Rapidminer has been implemented.
