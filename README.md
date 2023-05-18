# LSTM and Sherlock Holmes - INFO 3950 mini project 

<br> I had some prior exposure to LSTM models so I was curious as to how LSTM models could work with text. I decided to try the exercise from this website: https://machinelearningmastery.com/text-generation-with-lstm-in-pytorch/. I repurposed the code to build a very simple LSTM model that could be used for text generation. The text used was the Sherlock Holmes text from the lecture 26: https://nbviewer.org/url/courses.cit.cornell.edu/info3950_2023sp/lec26_ngram_lm.ipynb.</br>
<br> The Sherlock Holmes text is very large one, around 500,000 words. I only used the first 50,000 words in the text. I wanted to see how the model would perform with a the smaller text sample size. </br>
<br> I used Google Colab for this project so that I could use the recommended CUDA-capable GPU that is available through Google Colab in order to speed up the training time for my model. </br>
<br> I think the text generated from the smaller sample size is decent. Parts of the sentence are readable and reminiscent of Sherlock Holmes, but there are quite a few words that appear to be mispelled and as a whole the sentences do not make a lot of sense. Performance seems to have improved with a larger window size and I also tried a model with three layers which I think increased the model's ability to generate text more accurately.</br>
