<h1>Neural Network Experiments and Implementations</h1>

This repository presents a structured set of neural network experiments implemented from scratch and using standard libraries. The focus is not only on implementation, but on understanding how different models behave, where they fail, and why they are used.

The project progresses from basic numerical operations to advanced neural architectures such as MLP, CNN, RNN, and Hopfield Networks.



<h2>Tech Stack</h2>

- Python
  
- NumPy
  
- Pandas
  
- Matplotlib
  
- SciPy
  
- Scikit-learn
  

<h2>Project Structure</h2>

Neural-Network-Lab/ │ ├── Ex-1 NumPy/ ├── Ex-2 Pandas/ ├── Ex-3 SciPy/ ├── Ex-4 Plotting/ ├── Ex-5 Perceptron/ ├── Ex-6 XOR-MLP/ ├── Ex-7 Activation/ ├── Ex-8 MLP/ ├── Ex-9 CNN-RNN/ ├── Ex-10 Regression/ ├── Ex-11 Hopfield/ │ └── README.md


<h2>Experiments Breakdown</h2>

<h3>1. NumPy Operations</h3>

Basic array manipulation, matrix operations, and numerical computation.

<h4>Key Insight</h4>

Vectorization is critical for performance in machine learning pipelines.

<h4>Output</h4>

![Output Image](Experiment-1/Output(a).jpeg)

![Output Image](Experiment-1/Output(b).jpeg)

<h3>2. Pandas Data Handling</h3>

DataFrame creation, feature addition, and aggregation using group-by.

<h4>Key Insight</h4>
Data preprocessing is often more important than the model itself.

<h4>Output</h4>

![Output Image](Experiment-2/Output.jpeg)


<h3>3. SciPy Operations</h3>

Root finding, optimization, sparse matrices, and distance calculations.

<h4>Key Insight</h4>

Optimization is the backbone of training neural networks.

<h4>Output</h4>

![Output Image](Experiment-3/Output(a).jpeg)
![Output image](Experiment-3/Output(b).jpeg)



<h3>4. Function Visualization</h3>

Plotting sine wave using Matplotlib.

<h4>Key Insight</h4>

Visualization helps in understanding function behavior and model outputs.

<h4>Output</h4>

![Output Image](Experiment-4/Output.jpeg)


<h3>5. Perceptron Learning</h3>

Implements a basic perceptron using weight updates.

<h4>Key Insight</h4>

- Works only for linearly separable data
  
- Fails on XOR problem
  
<h4>Output</h4>

![Output Image](Experiment-5/Output.jpeg)

<h3>6. XOR Problem using MLP</h3>

Uses hidden layers to solve a non-linear classification problem.

<h4>Key Insight</h4>

Adding hidden layers introduces non-linearity, enabling complex decision boundaries.

<h4>Output</h4>

![Output Image](Experiment-6/Output.jpeg)

<h3>7. Activation Functions</h3>

Visualization of Sigmoid, ReLU, and Linear functions.

<h4>Key Insight</h4>

| Function | Behavior        | Problem            |
|----------|----------------|--------------------|
| Sigmoid  | Smooth         | Vanishing gradient |
| ReLU     | Fast, sparse   | Dead neurons       |
| Linear   | Simple         | No learning power  |

<h4>Output</h4>

![Output Image](Experiment-7/Output.jpeg)

<h3>8. Multi-Layer Perceptron (MLP)</h3>

Implementation using Scikit-learn.

<h4>Key Insight</h4>

MLPs approximate complexfunctions but require proper tuning.

<h4>Output</h4>

![Output Image](Experiment-8/Output.jpeg)

<h3>9. CNN and RNN Basics</h3>

- CNN: Convolution operation for feature extraction
  
- RNN: Sequence processing using temporal dependency
  
<h4>Key Insight</h4>

| Model | Strength              | Use Case        |
|------|-----------------------|------------------|
| CNN  | Spatial understanding | Images           |
| RNN  | Sequential memory     | Time series      |



</h4>Output</h4>

![Output Image](Experiment-9/Output.jpeg)

<h3>10. Linear Regression</h3>

Basic regression model using optimization.

<h4>Key Insight</h4>

Serves as the foundation for gradient-based learning.

<h4>Output</h4>

![OutputImage](Experiment-10/Output.jpeg)

<h3>11. Hopfield Network</h3>

Implements associative memory.

<h4>Key Insight</h4>

Recalls stored patterns from incomplete or noisy input.

<h4>Output</h4>

![Output Image](Experiment-11/Output.jpeg)

<h2>Model Comparison</h2>

| Model       | Type        | Limitation                    |
|------------|------------|-------------------------------|
| Perceptron | Linear     | Cannot solve XOR              |
| MLP        | Non-linear | Needs tuning                  |
| CNN        | Spatial    | Requires large data           |
| RNN        | Sequential | Vanishing gradient            |
| Hopfield   | Memory     | Limited capacity              |



<h2>What This Project Demonstrates</h2>

- Understanding of core ML foundations
  
- Implementation from scratch and library-based
  
- Ability to analyze model behavior
  
- Comparison of different architectures
  
<h2>How to Run</h2>

```
pip install numpy pandas matplotlib scipy scikit-learn python filename.py

```
