# NLP-Emoji-Predictor

This is group work of Lulu Wan, Qiqi Zeng and Su Shen 

Instead of using Softmax to pick out the most likely emoji, we predicted emojis according to cosine similarity between the sentence vector and its corresponding emoji vector.
There are 5 files in this source_code folder.

"29.ipynb": To test our model, print 'demo()' and run it. When you enter a sentence, the system will return an emoji. It is also available via this link:https://colab.research.google.com/drive/1Xnz48WJhbrMj6zfL79SYLkUkzcSuKaZy

"model": this folder contains 4 source code. To run the code in this folder, You need to download 'GoogleNews-vectors-negative300.bin', 'emoji2vec.bin' and the 'sample_data' from https://github.com/bfelbo/DeepMoji
 
"model/LSTMbaseline.ipynb": this source code applied the algorithm of the LSTM baseline
"model/LSTMemoji2vec.ipynb": this source code applied the algorithm of the LSTM emoji embedding
"model/CNNbaseline.ipynb": this source code applied the algorithm of the CNN baseline
"model/CNNemoji2ve.ipynb": this source code applied the algorithm of the CNN emoji embedding 
