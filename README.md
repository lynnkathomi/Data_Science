Navigate to the project directory:

bash

cd road-accident-severity-prediction
Install the required libraries:

bash

pip install -r requirements.txt
Run the Jupyter Notebook:

bash

jupyter notebook
Usage
After running the Jupyter Notebook, follow these steps:

Load the dataset.
Preprocess the data (cleaning, encoding categorical variables, etc.).
Train the linear regression model.
Evaluate the model's Date,Time,Weather Condition,Road Surface,Light Condition,Vehicle Speed (km/h),Traffic Control Present,Road Type,Accident Severity
10/2/2024,14:30,Rainy,Wet,Daylight,70,1,Highway,2
10/3/2024,21:45,Clear,Dry,Night with lights,90,0,Local road,3
10/4/2024,22:40,Foggy,Wet,Daylight,50,1,Residential,1
,,,,,,,,
,,,,,,,,
,,,,,,,,
[accident.csv](https://github.com/user-attachments/files/17523648/accident.csv)
performance using the provided metrics.
Evaluation Metrics
The model's performance is evaluated using the following metrics:

Mean Absolute Error (MAE): Average of the absolute errors between predicted and actual values.
Mean Squared Error (MSE): Average of the squared differences between predicted and actual values.
R-squared (R²): Proportion of variance in the dependent variable that can be predicted from the independent variables.
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or features you'd like to add.
