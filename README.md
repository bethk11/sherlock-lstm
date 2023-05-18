# LSTM and Sherlock Holmes 

<br> For my project, I decided to try the exercise from this website: https://machinelearningmastery.com/text-generation-with-lstm-in-pytorch/. I repurposed the code to build a very simple LSTM model that could be used for text generation. The text used was the Sherlock Holmes text from the lecture 26: https://nbviewer.org/url/courses.cit.cornell.edu/info3950_2023sp/lec26_ngram_lm.ipynb.</br>
<br> The Sherlock Holmes text is a large one, so I only used the first 50,000 words in the text. I wanted to see how the model would perform with a smaller text before trying a larger one. </br>
<br> I used Google Collab for this project so that I could use the recommended CUDA-capable GPU that is available through Google Collab in order to speed up the training time for my model. </br>
<br> I think the text generated for the smaller sample size is okay. Parts of the sentence are readable and reminiscent of Sherlock Holmes, but there are quite a few words that appear to be mispelled and as a whole the sentences do not make a lot of sense.</br>
