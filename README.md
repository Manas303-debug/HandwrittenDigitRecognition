# HandwrittenDigitRecognition
I tried the Hello World! of machine lear ning, just for practice purposes,

Action plan:
1. We loaded the train, test and validation Data
2. We outlined the model and chose an activation function
3. Declared some parameters and hyperparameters like Depth and Width of layers
4. Chose the apporpriate optimizer
5. Split the dataset into batches for faster Learning
6. Made it learn(Backpropagation)

Other details:
Each photo was 28by28 pixels we represented them as a 784x1 matrix,
the no. of input units were therefore, 784, where each pixel represents a number between 0 and 1
0-White and 1-Black
Our model has 2 hidden layers
The no. of output layers is equal to the outputs we expect which are numbers betwee 0 and 9,
so 10 output units, we have used softmax for the last layer

Accuracy on the train data was 96%
