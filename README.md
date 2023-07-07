# Vectorized-Similarity-Search-in-Multi-modal-Data
1. Introduction
6 Nowadays, the aim of machine learning and artificial intelligence is to train the datasets we collect under the current
7 condition and predict the trend in the future, doing enormous calculations that human beings will take for a while. Traditional
8 machine learning focus on a single type of data, such as text, images, xml, etc. However, this is sort of violating what a
9 machine can really do because a machine exports images, text, audio,..., and all kinds of data synchronously. It is also like
10 us, we hear, we smell, we feel at the same time. So, to make a machine learn all kinds of datasets at the same time, we need
11 to let the machine analyze multi-model data.
12 Multi-modal data spans data into different dimensions and different types. Each type might have different features. It
13 seems like combining all those dimensions of data is appealing, but in practice, embedding large scale data is a challenge
14 because it might have noise and conflicts between the dimensions. In this project, we focus on two dimensions of input, text
15 and image. We finally want to achieve that there is a connection between the dimensions, such as if we input a text, we will
16 find the match of its image that best fits the describtion. On the other hand, if we input an image, we will find the match of
17 its image that best describes features of the image.
