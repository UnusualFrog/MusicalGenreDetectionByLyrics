# Steps for Running Model

## Step 1 - Download dependencies
```
pip install --upgrade pip
pip install -r requirements.txt
```

## Step 2 - Train Model
- Run train.py to train and save models and vocabularies to local files

## Step 3 - Unseen Predictions
- Run genius_predictions to make predictions on unseen data using the genius API
- Once running input option 1 from the terminal to make a prediction
- Type in the name of a song you would like to predict (for increased accuracy include the artist's name, some songs share names creating ambiguity)
```
# Example Usage (user inputs denoted by >)
Select an option
0. Exit Program
1. Predict new song
> 1
Please enter the title of a song (and optionally the artist name): 
> Compton Kendrick Lamar
Searching for "Compton Kendrick Lamar"...
Done.
Founds Song:  "Compton" by Kendrick Lamar:
    [Produced by Just Blaze]
    
    [Verse 1: Kendrick Lamar]
    Now everybody serenade the new faith of Kendrick...
Compton by Kendrick Lamar (Ft. Dr. Dre)
lr: rap (82.28%)
nb: rap (100.00%)
svm: rap (100.00%)
rf: rap (79.02%)
```
