# IMDB Reviews Sentiment Analysis


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#code-usage">Code Usage</a>
      <ul>
        <li><a href="#Regression">Regression</a></li>
        <li><a href="#Classification">Classification</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#reference">Reference</a></li>    

    
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

- The task of classifying sentiments of texts (for example movie or product reviews) has high practical significance in online marketing as well as financial prediction. This is a non-trivial task, since the concept of sentiment is not easily captured.
- As part of the model building five different approaches where used and please go through the notebooks for more understanding.


![Product Name Screen Shot](https://github.com/chaitanya2593/IMDB_Sentiment_Analysis/blob/main/overview.png)




<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Python
  * Data science packages 
  * tensorflow
* Google Colab - (Please use colab as it has already most of the packages installed)



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

- Code development is performed in the  Google colab notebooks. Colab already has 
required data science packages preinstalled and provided the pip (python package installer) commands where it is required.

- For few data I/O operations like saving the processed files and models, I have used my personal drive.
- 
### Prerequisites

* The user should have an google account and access to the google drive as well.
* Kindly install the packages stated in the notebooks.




<!-- USAGE EXAMPLES -->
## Code Usage  


All the Approaches are summarized in 2 notebooks.
- 1_Multi_models_IMDB_Sentiment_classification.ipynb
  1. TFIDF + classical statistical model 
     - Random Forest 
     - Naive Bias
  2. LSTM classification model
      - Untuned 
      - Tuning using the Keras-Tuning
  3. LSTM model, where the embeddings are initialized with pre-trained word vectors
      - GLOVE Embedding - Wiki 2014 dump
      - GLOVE Embedding - Twitter Data
  4. fastText model - From facebook

- 2_Transformer_Bert_IMDB_Sentiment_classification.ipynb
  - In this script, BERT pretained transformer has been used for training.
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the GNU License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact


1. [VS Chaitanya Madduri](https://github.com/chaitanya2593) | [LinkedIn](https://www.linkedin.com/in/v-s-chaitanya-madduri-2886447a/)


Project Link: [https://github.com/chaitanya2593/IMDB_Sentiment_Analysis.git](https://github.com/chaitanya2593/IMDB_Sentiment_Analysis.git)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->  
## Reference

- LSTM - https://slundberg.github.io/shap/notebooks/deep_explainer/Keras%20LSTM%20for%20IMDB%20Sentiment%20Classification.html
- LSTM + GLOVE - https://www.kaggle.com/code/samarthsarin/simple-guide-for-lstm-and-glove-embeddings/notebook
- Transformer Bert - https://www.analyticsvidhya.com/blog/2021/12/fine-tune-bert-model-for-sentiment-analysis-in-google-colab
- Keras-Tuner - https://medium.com/analytics-vidhya/hypertuning-a-lstm-with-keras-tuner-to-forecast-solar-irradiance-7da7577e96eb

<p align="right">(<a href="#readme-top">back to top</a>)</p>


