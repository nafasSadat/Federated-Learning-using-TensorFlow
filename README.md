# Federated-Learning-using-TensorFlow
Implement Client Selection in Federated Learning envirnment using Tensorflow in Google Colab. <br>
Steps: <br>
1.Preprocess Dataset and sample Client from Tensorflow Lib <br>
2.Create a helper IID Dataset from public MNIST Dataset <br>
3.Create Global and Helper Model in the server <br>
4.Train the Helper model with IID Dataset <br>
5.Select Clients having higher IID data.<br>
6.Send the Global model to the selected clients. <br>
7.Clients train the Global model using their local data. <br>
8.Send the Global model back to the server. <br>
9.Server Aggrigate the updated model received from clients and create new model. <br>
