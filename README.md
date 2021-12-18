# Spring-2022-Programming-Challenge-ISI

<h3>Summary</h3>
The textual data obtained from Telegram group <b>https://t.me/CryptoComOfficial</b> from 05-01-2021 to 05-15-2021 has been pre-processed by removing punctuation, stop words & non-English words. The obtained dataset with SHIB/DOGE keywords has been processed by Sentiment Analyzer SentimentIntensityAnalyzer from nltk.sentiment module. 

<br>
<h3>Number of msgs per day & the average sentiment per day can be seen in the following plot:</h3>

![alt text](https://github.com/pia-nyk/Spring-2022-Programming-Challenge-ISI/blob/master/sentiment%20plot%20by%20date.png)

<b>Hovering on the dots will give additional information about the number of msgs per day</b>, which can also be analyzed from the size of the dots on the plot. The color of the plot determines the sentiment type which can be found in the legend provided.

<h3>Steps to run the file in Google Colab environment:</h3>
<ol>
  <li> Open Google Drive -> Collab Notebooks </li>
  <li> Create a folder ISI</li>
  <li> Add the reults.json & preprocess.ipynb files to this folder </li>
  <li> Open preprocess.ipynb on drive </li>
  <li> Run all the cells in the colab environment </li>
  <li> For the 3rd cell (while mounting drive), you will receive a prompt to permit the notebook to access google drive. Click on Connect to Google Drive. Select account & click on allow</li>
</ol>
