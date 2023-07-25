# MultiModal-Sentiment-Analysis_CM_BERT

The project “Multimodal Sentiment Analysis” aims to enable machines to recognize,
interpret, and express emotions. The analysis of the sentiment of the users and people using the
different features from the text, audio, etc. make it easier to understand the need of the different
behavior patterns of the user on social media. Sentiment analysis has many practical
applications in fields such as marketing, social media, and public opinion analysis. Also the
application of Natural Language Processing can be highly explored and understood in the
process of understanding the sentiment and future planning can be done in designing the
services to the users.
 In this project, we focused on analysing and developing a model in which we used the BERT
transformer for natural language processing and utilising the attention methods by combination
of data of both text and audio to detect and predict the kind of sentiment contained in the dataset
provided for training and testing of the model.
 The model we used for the NLP processing is the pretrained BERT large, containing a stack
of about 24 encoders and is pretrained on about 340 million parameters in place of the BERT
base model which has only 12 layers of encoders and is pretrained on 110 million parameters.
We used the proper amount of training parameters to fine-tune the BERT model and improve
the running time of the processing done by the BERT.
 To fuse the result of text processing with audio processing our model evaluated the weight
of each word in different modalities to adjust the weight of each word through the interaction
between text and audio modality. To reduce the influence of padding sequence, we introduced
a mask matrix, in which we used 0 to represent the token position and −∞ to represent the
padding position. After obtaining the multimodal attention matrix, our model multiplies it with
the value of the masked multimodal attention.
 By using our proposed model, we processed the input of our text and audio dataset to get
the result as what kind of sentiment the user depicted by themself according to the respective
videos in the dataset. The result of the model was used to check and report the performance of
our model by using different plots and performance metrics. The final model we built
performed satisfactorily according to our expectations
