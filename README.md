
# What I Learned

### Concept of Neural Networks
Neural networks are fascinating machine learning algorithms inspired by how our brains work. They’re designed to recognize patterns and learn from data, much like how we process information. At their core, neural networks consist of interconnected layers of nodes (neurons), each transforming input data through weighted connections to produce an output.

- **Neurons**: These are the building blocks of neural networks, similar to biological neurons. Each neuron takes in inputs, processes them, and sends the output to the next layer.
- **Layers**: Neural networks are structured in layers:
  - **Input Layer**: This is where the data first enters the network.
  - **Hidden Layers**: These intermediate layers transform the data using weighted connections and activation functions.
  - **Output Layer**: This layer delivers the final result after processing.
- **Weights and Biases**: Each connection between neurons has a weight that adjusts during training, determining the strength of that connection. Biases help the model adapt more flexibly to the data.

### Concept of a Perceptron
A perceptron is the simplest type of neural network and acts as a foundational element for more complex networks. It functions as a binary classifier, mapping input features to binary outputs by evaluating a weighted sum of inputs.

- Perceptrons can compute basic logical functions like AND, OR, and NAND. By linking multiple perceptrons together, we can create systems that tackle more intricate computations.

**Key Features**:
- **Inputs**: Each input has a corresponding weight that signifies its importance.
- **Weights and Bias**: Weights are adjusted during training, and a bias term shifts the decision boundary.
- **Weighted Sum**: The perceptron computes a weighted sum of the inputs and adds the bias.

### Sigmoid Neuron
A sigmoid neuron builds on the concept of a perceptron, computing a weighted sum of its inputs but using a sigmoid function for output.

- The sigmoid function has a smooth curve, providing a well-defined gradient, which is crucial for training.
- Sigmoid neurons can model non-linear relationships between inputs and outputs, making them more powerful for complex problems.
- The output of the sigmoid function ranges between 0 and 1, which is especially useful in binary classification tasks, as it reflects the likelihood of a certain class.



