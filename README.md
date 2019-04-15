# Image Classifier DeepLearning

This is a Tutorial to Learn about Object Detection using Tensor Flow already trained models.

## Application Ideas
Leverage the new TensorFlow.Hub tool to load already pretty well trained models, and then do a Transfer Learning to work with a  specific subset of objects to be detected - namely urban transportation vehicles and pedestrians.

## Challenges
**Problem 1**: Running the Classifier model every frame is very taxing and loses track of "already identified" objects - rework.

**Fix Strategy**: use a combination of Classifier and Tracker.

**Problem 2**: Tracker not working properly when there is superposition of vehicles (i.e. vehicle movements in an intersection).
