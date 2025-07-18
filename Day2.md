# Neural Networks
## What are Neural Networks
Neural Networks are computational models composed of layers of interconnected nodes(neurons), neural networks process input data, learn patterns, and make predictions or classifications.

The basic building blocks of a neural network include input layers, hidden layers and output layers.


<img width="923" height="576" alt="image" src="https://github.com/user-attachments/assets/444aadaf-253a-411a-a32b-1103a99589fb" />


## Components of a Neural Network
1. Input Layer: The first layer that receives the initial input data.
2. Hidden Layer: Intermediate layers between the input and output layers. These layers enable the network to learn complex patterns and representations from the input data.
3. Output Layer: The final layer that produces the network's output. The number of neurons in this layer depends on the nature of the task.


 <img width="825" height="703" alt="image" src="https://github.com/user-attachments/assets/4dbdf520-b2b1-4609-96c6-a80d38261c6e" />

## Types of Neural Networks
Mainly, Neural Networks are of 3 types:
1. Feedforward Neural Network(FNN):
Feed-forward neural networks transmit data in one direction, from input to output, without feedback loops, making them suitable for tasks like pattern recognition and classification.

A sequence of inputs enters the layer and is multiplied by the weights in this model. The weighted input values are then summed together to form a total, which is transformed by the Activation function to add non-linearity to it and then gives the output.


<img width="1034" height="473" alt="image" src="https://github.com/user-attachments/assets/d7c37b66-dd01-40cf-9af8-121dbf8f06de" />

### Feedback Loop in Neural Network:
Backpropagation is the essence of neural net training. It is the practice of fine-tuning the weights of a neural net based on the error rate (i.e. loss) obtained in the previous epoch (i.e. iteration). Proper tuning of the weights ensures lower error rates, making the model reliable by increasing its generalisation.


<img width="1122" height="708" alt="image" src="https://github.com/user-attachments/assets/61588684-3c1d-4a5a-ae2a-ab95532b76d4" />


<img width="1021" height="715" alt="image" src="https://github.com/user-attachments/assets/6562db34-5d2b-4eea-a52b-0ada5cd58717" />

## 2. Convolutional Neural Network(CNN):
A simple CNN designed for image classification. It includes convolutional layers with activation functions, max-pooling, fully connected, flatten and a dense layers with a output activation functions for classification tasks.

It extracts the feature of image using convolutional layers and convert it into lower dimension without loosing its characteristics.


<img width="986" height="542" alt="image" src="https://github.com/user-attachments/assets/7f6cb9ef-ea85-4dd3-adb3-5a01bb969ff6" />



<img width="1486" height="689" alt="image" src="https://github.com/user-attachments/assets/904e055e-55db-4c69-9b3b-ef4fa859ec0f" />


## 3. Recuurent Neural Networks(RNN):
Recurrent neural networks(RNNs) are a class of neural network that are helpful in modelling sequence data. Derived from feedforward networks, RNNs exhibit similar behaviour to how human brains function.  

<img width="1162" height="356" alt="image" src="https://github.com/user-attachments/assets/67f18348-1105-4ccd-9da3-ace6e68ba16f" />

Theyhave feedback connections that allow them to retain information from previous time steps, enabling them to capture temporal dependencies. This makes RNNs well-suited for tasks like language modelling, speech recognition, and sequential data analysis.

<img width="1506" height="716" alt="image" src="https://github.com/user-attachments/assets/c6079885-5aee-4711-9e08-82d1c826b6b7" />



## Why Neural Networks for GenAI?
Neural Networks are at the forefront of GenAI, offering powerful tools for pattern recognition, generative modelling, creative content creation, adaptability, and realistic simulation. Their ability to capture and mimic complex patterns in data makes them essential for pushing the boundaries of what is possible in the generation of artificial intelligence.
