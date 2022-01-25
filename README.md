# WhatsNext

In this project I create a recurrent neural network model that can predict the next word of my sentence. I got the inspiration for it from Google’s Gboard. 

Data was collected after exporting one of my WhatsApp’s chats. After processing it to filter out emojis, links and other data that I wouldn’t want my model to predict, a recurrent neural network consisting of an Embedding layer and several LSTM layers was created and trained. 
WhatsNext is able to predict words which I commonly use in my parlance as it has been trained on my own data.
