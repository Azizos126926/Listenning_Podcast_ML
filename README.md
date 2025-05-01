# Predict Podcast Listening Time: Playground Series - Season 5, Episode 4

                                         
Goal: Predict listening time of a podcast episode
# <img width="100" alt="transparent logo" src="https://github.com/user-attachments/assets/6b97b9f9-372c-456c-a2eb-4ad9331424cb" /> ✅ Result of competition: top 390 / 3310 
Public Score: 11.933
Private Score: 11.84

# Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Podcast Listening Time Prediction dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.
# Files
train.csv - the training dataset; Listening_Time_minutes is the target
test.csv - the test dataset; your objective is to predict the Listening_Time_minutes for each row
sample_submission.csv - a sample submission file in the correct format.
Notebook: S5E4: Score 11.84 Private, Rank 390


# Participation
8,639 Entrants

3,454 Participants

# Evaluation
Submissions are scored on the root mean squared error(RMSE).

For each id in the test set, you must predict the Listening_Time_minutes of the podcast. The file should contain a header and have the following format:

id,Listening_Time_minutes
750000,45.437
750001,45.437
750002,45.437
etc.
