Task 1:

This code uses only built in python libraries, and so should be able to run like any other Jupyter Notebook file.
This code should be reproducable to a certain degree, as all random seeds have fixed values.
In order to obtain the most optimal resutls, use these values:
- Learning rate: 0.9
- Epochs: 50
- Batch Size: 100
- Optimiser: SGD
- Learning Rate Decay: 0.001
- Dropout - 0.2
- Neuron Size: 250

Task 2:

Like Task 1, this code uses standard built in Python libraries, and can be run like a normal Jupyter Notebook file.
However, the dataset used is an external dataset, and so the path of its location must be set.
By default, the code will run if the "archive" folder is in the same directory as the code.
I have slightly modified the dataset I obtained, and the file is too large to upload to GitHub (55-100MB),
and so the folder I have used is available at the following link:

https://1drv.ms/u/s!Agrx7FPGiUW2grQ75S1JOz2FsZw1MA

Please download this folder as it is the only way to ensure results will be similar to my tests.

In order to obtain the most optimal results, use these values:
- Learning rate: 0.01
- Epochs: 15
- Batch Size: 64
- Optimiser: SGD
- Weight Decay: 0.001
- Dropout - 0.5