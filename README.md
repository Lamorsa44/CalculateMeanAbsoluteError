# Mean Absolute Error Calculator

This application calculates the Mean Absolute Error (MAE) between actual values and predicted values. MAE is a common metric used in statistics and machine learning to evaluate the accuracy of predictions.

### ***Only use numbers or it breaks😈***

## What is Mean Absolute Error?

Mean Absolute Error is the average of the absolute differences between predicted values and actual values. It measures the average magnitude of errors in a set of predictions, without considering their direction.

The formula is:
```
MAE = (1/n) * Σ|actual - predicted|
```
Where n is the number of observations.

## Features

The application offers two modes of operation:
1. Calculate MAE by providing lists of actual values and predictions
2. Calculate MAE by directly providing the list of absolute differences

## Requirements

- Java Runtime Environment (JRE) 17 or higher
- Terminal/Command Prompt for input

## How to Run

### Using the JAR file

1. Navigate to the directory containing the JAR file
2. Run the command: `java -jar MedianAbsError.jar`

### From source code

1. Compile the source code: `javac src/Main.java -d out/production/MeanAbsoluteError`
2. Run the compiled class: `java -cp out/production/MeanAbsoluteError Main`

## Usage Instructions

1. When prompted, enter the number of values you want to process
2. Select a mode:
   - Mode 1: Enter actual values followed by predicted values
   - Mode 2: Enter absolute differences directly
   - Mode 0: Exit the application
3. The application will calculate and display the Mean Absolute Error

## Example

```
Number of total values: 
3
Mode 1 | List with values and predictions
Mode 2 | List of absolute differences
Mode 0 | Exit
1
Enter the values: 
10 15 20
Enter the predictions: 
12 14 21
Result = 1
```

In this example:
- We have 3 values
- Actual values: 10, 15, 20
- Predicted values: 12, 14, 21
- Absolute differences: |10-12|=2, |15-14|=1, |20-21|=1
- Mean Absolute Error: (2+1+1)/3 = 1.33, which is rounded to 1 in the output

## Notes

- The application rounds the result to the nearest integer
- Input values should be integers
- To exit the application, select Mode 0
