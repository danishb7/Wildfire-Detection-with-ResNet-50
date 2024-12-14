The Wildfire Dataset project involves applying multiple image
processing techniques to multiple datasets and comparing
the results. This study involves only the classification tasks.
The ResNet model is used for training on multiple datasets
with the same structure, optimizer, loss function, learning rate,
etc., and then test the trained model on the remaining datasets.
The idea is to analyze which dataset is the most optimal
and can generalize information across all other datasets.

Link to dataset - https://drive.google.com/drive/u/2/folders/11EFyD1yJwMsaDtoavPTov4q4kkJJFsB1

Results:-
![pic](https://github.com/user-attachments/assets/86a6fead-bb74-46a7-9a0c-0be222ec9920)

Based on the values, the ResNet model trained on the
FLAME dataset has the highest average testing accuracy
(73.23%) and the highest F1 score (0.82) when tested on
other models. It can be concluded that FLAME is the best
dataset (among the 7 datasets used for training) in terms of
generalization results.
