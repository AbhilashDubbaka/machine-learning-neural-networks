# Neural Networks Coursework

This machine learning coursework on neural networks was completed as part of MSc Computing Science at Imperial College London.

## How to run our predict_hidden for Part 2 and 3
Input either the entire dataset or just the X_input data (first three columns). We are expecting a text file. Replace "ROI_dataset.dat" with your own dataset
```
if __name__ == "__main__":

    dataset = np.loadtxt("ROI_dataset.dat")

    predictions = predict_hidden(dataset)
    print("Predictions:")
    print(predictions)

```
Once you include your dataset as above in ```learn_ROI.py``` or ```learn_FM.py```, run ```python3 learn_ROI.py``` or ```python3 learn_FM.py```.