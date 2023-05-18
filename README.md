# LSTM and Sherlock Holmes 

**INFO 3950 Mini Project**

<br> I had some prior exposure to LSTM models so I was curious as to how LSTM models could work with text. I decided to try the exercise from this website: https://machinelearningmastery.com/text-generation-with-lstm-in-pytorch/. I repurposed the code to build a very simple LSTM model that could be used for text generation.</br> 
<br>The text used was the Sherlock Holmes text from lecture 26 and the zipfile for the data is included. The original text was sourced from Project Gutenberg.</br>
<br> The Sherlock Holmes text is very large one, around 500,000 words. I decided to just create a text corpus of the first 50,000 words. I wanted to see how the model would perform with a the smaller text sample. </br>
<br> I used Google Colab for this project so that I could use the recommended CUDA-capable GPU that is available through Google Colab in order to speed up the training time for my model. </br>
<br> I think the text generated from the smaller sample size is decent. Parts of the sentence are readable and reminiscent of Sherlock Holmes, but there are quite a few words that appear to be mispelled and as a whole the sentences do not make a lot of sense. Adjusting window size didn't seem to change performance significantly, but using a three layer model did seem to have more accurate results.</br>
