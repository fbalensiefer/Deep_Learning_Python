# How to use Deep Learning algorithms in Python
**AI:** Artificial intelligence (AI) is a computer system trained to perceive its environment, make decisions, and take action. AI systems rely on learning algorithms, such as machine learning and deep learning, along with large sets of sensor data with well-defined representations of objective truth.

**Machine learning:** We use machine learning as shorthand for “traditional machine learning”—the workflow in which you manually select features and then train the model. When we refer to machine learning we exclude deep learning. Common machine learning techniques include decision trees, support vector machines, and ensemble methods.

**Deep learning:** A subset of machine learning modeled loosely on the neural pathways of the human brain. Deep refers to the multiple layers between the input and output layers. In deep learning, the algorithm automatically learns what features are useful. Common deep learning techniques include convolutional neural networks (CNNs), recurrent neural networks (such as long short-term memory, or LSTM), and deep Q networks.

**Algorithm:** The set of rules or instructions that will train the model to do what you want it to do.

**Model:** The trained program that predicts outputs given a set of inputs.

In this example I will rely on Keras.
Keras is an open-source neural-network library written in Python.
[Keras.io](https://keras.io/)
    
I reproduce the Example from [*Michael Grogan*](https://datascienceplus.com/keras-regression-based-neural-networks/)
A neural network consists of:
    - **Input layers**: Layers that take inputs based on existing data
    - **Hidden layers**: Layers that use backpropagation to optimise the weights of the input variables in order to improve the predictive power of the model
    - **Output layers**: Output of predictions based on the data from the input and hidden layers

