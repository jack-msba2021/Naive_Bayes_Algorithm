# Spam eMail Detection using Naive Bayes Classification Algorithm
![enter image description here](https://computing.which.co.uk/hc/article_attachments/115003185029/Spam-email-guide.jpg)

## Project Description
This project practices training and predicting with sklearn Naive Bayes while using the Gaussian method for model training. The project example uses email data and attempts to train the model to properly label messages as Spam or Not Spam. The model was trained using 702 emails (equally divided into spam and non spam categories) and tested on 206 emails. Before running the model, the data was cleaned by creating a dictionary for all words found in the files, removing non-alphabetical words, and extracting the 3000 most common words into a final dictionary. Lastly, a label and word frequency matrix was generated. After running the model an accuracy score was printed.

## Steps

 1. Data cleaning
 2. Generating a word frequency matrix
 3. Training and testing the model
 4. Interpreting the results

## Requirements
The following can be used to run Python code:
 - [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
 - [Jupiter Notebook](https://jupyter.org)

### Installation
The following packages are required to run this project:
```python
import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import accuracy_score
from google.colab import drive
drive.mount('/content/drive')
```
### Drive
After downloading and opening the the data file, upload it to your Google Drive with the following folder structure: 
```python
/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA02/Data
```
## Project File
Access the project [here](https://colab.research.google.com/drive/1jX1oEV3FwhmYO7jaUhchNvEUBszmJckG?usp=sharing).

## Trouble Shooting
Make sure to mount your drive before running the code.

## Authors
[Jack Taylor](https://www.linkedin.com/in/jack-taylor-su/)

## Credits and Acknowledgments
Thank you Professor [Arin Brahma](https://github.com/ArinB) of Loyola Marymount University for providing the file template.

## License
[MIT](https://choosealicense.com/licenses/mit/)
