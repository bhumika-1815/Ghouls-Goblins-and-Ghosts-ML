# Ghouls-Goblins-and-Ghosts-ML
Overview
After a month of making scientific observations and taking careful measurements, we’ve determined that 900 ghouls, ghosts, and goblins are infesting our halls and frightening our data scientists. When trying garlic, asking politely, and using reverse psychology didn't work, it became clear that machine learning is the only answer to banishing our unwanted guests.
So now the hour has come to put the data we’ve collected in your hands. We’ve managed to identify 371 of the ghastly creatures, but need your help to vanquish the rest. And only an accurate classification algorithm can thwart them. Use bone length measurements, severity of rot, extent of soullessness, and other characteristics to distinguish (and extinguish) the intruders.

#Dataset
This dataset is sourced from Kaggle : https://www.kaggle.com/c/ghouls-goblins-and-ghosts-boo/data

#DataSet Description:
File descriptions
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format

Data fields
id - id of the creature
bone_length - average length of bone in the creature, normalized between 0 and 1
rotting_flesh - percentage of rotting flesh in the creature
hair_length - average hair length, normalized between 0 and 1
has_soul - percentage of soul in the creature
color - dominant color of the creature: 'white','black','clear','blue','green','blood'
type - target variable: 'Ghost', 'Goblin', and 'Ghoul'
