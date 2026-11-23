Alleah MacSteves

# week5-image-classifier


# Part 1 — Build Your Dataset

## 1.1 Pick a Task

For this project, I chose to build an image classifier that can recognize two different desk objects: pen and phone

My two classes are:
1. Pen
2. Phone


I chose these objects because they are everyday items that are easy to photograph using my phone camera. They also have different shapes and appearances, which makes them good objects to test with an image classification model. I wanted to see how accurately the model could recognize each object and whether changing the environment would affect its predictions.



### 1.3 Record Your Conditions

Record                      My Conditions
Where you were              At a wooden table in my home
Lighting                    Indoor lighting 
Background                  Dark wooden tabletop
Distance                    1-2 feet from the objects
Angles                      Mostly angled and overhead views, with some straight-on views
Whose hands/ whose objects  My own objects



### 2.3 Explain Your Results

The model performed better when identifying the phone than the pen. It correctly identified 4 out of 5 phone tests and 3 out of 5 pen tests. The phone had consistently high confidence percentages, while the pen had lower confidence.

I noticed that the model struggled when either object was held sideways or at a different angle. This shows that the model does not always recognize objects when their appearance or orientation changes. I learned that AI models can perform well with familiar images but still struggle with changes in the testing environment.
