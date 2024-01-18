# Federated-Learning-using-TensorFlow
Implement Client Selection in Federated Learning envirnment using Tensorflow in Google Colab.
Steps: <br>
1.Preprocess Dataset and sample Client from Tensorflow Lib 
2.Create a helper IID Dataset from public MNIST Dataset
3.Create Global and Helper Model in the server
4.Train the Helper model with IID Dataset
5.Select Clients having higher IID data.
6.Send the Global model to the selected clients
7.Clients train the Global model using their local data.
8.Send the Global model back to the server.
9.Server Aggrigate the updated model received from clients and create new model.
