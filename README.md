This repository contains a group project work for Team Beanstalk (Hamoye) for Age and Gender Detection using CNN (Conventional Neu
ral Networks) model to analyze face pictures of different genders and age groups. 

The dataset includes a CSV of facial images that are labeled on the basis of age, gender, and ethnicity, and it includes 27305 rows and 5 columns, age, ethnicity, gender, img_name and pixels. 
The link to the dataset can be found at:

https://www.kaggle.com/datasets/nipunarora8/age-gender-and-ethnicity-face-data-csv.


Log:


03/02/23: 
- Semmyinc created the repository.
- He provided the template of the project and assessed the data.


04/02/23:
- Zakaria set the Methodology of the project. 
- He provided data collection by using kaggle API.
- He did a Wrangling for the data by dropping unecessary columns.
- He extracted the pixels column (the input varriables).
- He made a visualization for 30 random images (rows) from the data.
          

07/02/23:
- Zakaria contributed in features engineering part.
- He converted the data to numpy array.
- He reshaped the input values to (48, 48, 1) shape.
- He normalized the input values by dividing them by 255.
- He performed a train test split to the data.

08/02/23:
- Zakaria contributed in data Modeling and Evaluation.
- He made a Multi-output CNN (Conventional Neural Networks) Model.
- He fitted the model to train the data with 50 epochs, batch size of 64, with callback parameter.
- He evaluated the model and got the following results:
    - Loss:  91.15288543701172
    - Age Loss:  90.85930633544922
    - Gender Loss:  0.2935935854911804
    - Age MAE:  6.899173259735107
    - Gender Accuracy:  0.8688040375709534

- He plotted the loss curves for age and gender using Matplotlib.
