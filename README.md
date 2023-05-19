# LSTM and Sherlock Holmes 

**INFO 3950 Mini Project**

<br> I had some prior exposure to LSTM models so I was curious as to how LSTM models could work with text. I decided to try the exercise from this website: https://machinelearningmastery.com/text-generation-with-lstm-in-pytorch/. I repurposed the code to build a very simple LSTM model that could be used for text generation.</br> 
<br>The text used was the Sherlock Holmes text file from lecture 26: https://nbviewer.org/url/courses.cit.cornell.edu/info3950_2023sp/lec26_ngram_lm.ipynb. The zipfile for the data is included.</br>
<br> The Sherlock Holmes text is a relatively large one with around 500,000 characters. I decided to create a text corpus of the first 50,000 characters to train my model with. I wanted to see how the model would perform with a the smaller text sample. </br>
<br> I used Google Colab for this project so that I could use the recommended CUDA-capable GPU that is available through Google Colab in order to speed up the training time for my model. </br>
<br> I think the text generated from the smaller sample size is pretty good and the text is somewhat readable. Adjusting window size didn't seem to change performance significantly, but using a three layer model did seem to have more accurate results.</br>
