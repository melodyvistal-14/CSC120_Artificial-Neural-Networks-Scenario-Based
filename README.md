# CSC120_Artificial-Neural-Networks-Scenario-Based

Artificial Neural Networks: Scenario-Based

1. Answer
      - A neural network is similar to the human brain because it connects thousands of artificial neurons, just as we have billions of natural neurons in our brain. Our neurons receive input from other neurons and process them; similarly, the artificial neurons receive input from other neurons and process it. Through millions of such connections, neural networks learn and take decisions.

2. Answer
       - They are known as Hidden Layers, where the simple patterns in the input data are mapped onto more sophisticated ones until the network is ready to make its decision in the output layer.

3. Answer
       - Backpropagation is done by feeding back the error ( the rose which was classified wrong as a tulip ) . Calculate the error and back propagate it in the system to change the weights of each neuron so that it can identify the rose better next time .

4. Answer
       - When the task is to detect binary fraud, it is necessary to apply the Sigmoid activation function to the output layer since it will provide an output from 0 to 1 that represents the probability directly – 0 means Safe and 1 means Fraudulent.

5. Answer
      -  ReLU is good for activation functions for  the deep layers because they produce an output and equal to the input value if positive and zero if negative, where f(x)=max(0,x). This helps avoid the vanishing gradient problem.

6. Answer
   - A CNN is  suit for that problem , it is because of  ability to identify local features through the use of convolutional layers, retaining spatial information, which  why its not possible with a Feedforward Network due to its tendency to treat every single pixel separately.

7. Answer
       - It is more better to use the RNN model in order to suggest the next word due to the sequential processing of the text and the presence of a hidden layer, so that retains information about the previously processed words, which helps predict the next one based on the context.

8. Answer
       - In that case , it need to employ the Pooling Layer, because its  more specifically a Max Pooling layer, which involves a placing filter (for example, 2×2) on the feature map and extracting it the highest value, resulting in the down sampling of spatial dimensions from 32×32 to 16×16.

9. Answer
        - Its called Overfitting, because the model has memorized the training data instead of learning generalizable patterns, so it fails on new, unseen data.

10 . Answer 
        - The reason why is that ANNs operate like black boxes; hence, the decision is distributed among the millions of weights and neurons, making it hard to determine the exact pixels that cause the decision without using any special explainability techniques. 
