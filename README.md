# Google-QA-labelling

In our quest to enhance the quality and relevance of question-answer interactions, we turned to the invaluable Google-QUEST Q&A Labeling dataset and harnessed the power of artificial intelligence. We chose BERT, an uncased pre-trained model, to generate dense representations of various texts. These embeddings were then thoughtfully combined and fed into dense layers with tanh activation, with dropout in place to tackle overfitting.

To efficiently distill the information from these embedded vectors, we implemented a BiLSTM architecture. We employed ReLU activation in the dense layers and sigmoid activation in the output layer to ensure that the probabilities were accurately preserved.

Addressing the issue of label imbalance, we performed random oversampling at two different rates, 5% and 15%, and the results were quite favorable after training each model for a mere 10 epochs. This approach has brought us significant strides in improving the question-answer experience, bridging the gap in traditional Q&A systems with the help of cutting-edge AI techniques.

This project has been done by - Vipul Sarode, Sharvil Arjunwadkar, Aadil Zikre
