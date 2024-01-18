# Federated-Learning-using-TensorFlow
Implement Client Selection in Federated Learning envirnment using Tensorflow in Google Colab.
Steps:
Preprocess Dataset and sample Client from Tensorflow Lib
Create a helper IID Dataset from public MNIST Dataset
Create Global and Helper Model in the server
Train the Helper model with IID Dataset
Select Clients having higher IID data.
Send the Global model to the selected clients
Clients train the Global model using their local data.
Send the Global model back to the server.
Server Aggrigate the updated model received from clients and create new model.
