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


### Part 3: Breaking the Model

I tested my model under different conditions, including changes in lighting, background, and distance. The model struggled much more with recognizing the pen than the phone. When I changed the lighting and background, the model had difficulty recognizing the pen. However, it recognized the phone with 80% confidence under different lighting and 99% confidence with a different background.

These tests showed me that my model is better at recognizing the phone than the pen. It also showed that changes in the environment can affect how accurately an AI model identifies objects. The model needs more varied training images to improve its ability to recognize objects under different conditions.


### Part 4: Diagnose and Fix

Hypothesis:

I think the model struggles to recognize the pen because my training images did not include enough variety in angles and lighting. I believe adding more pen images taken from different angles and lighting conditions will help the model recognize the pen more accurately.


### Part 4.2: Changes Made

I originally added additional pen images, but some included my face and other parts of my appearance. I noticed that the model started identifying me as a pen, even when I was not holding one. I removed those images and kept the training images focused on the pen itself. After making this change and retraining the model, it began recognizing the pen more accurately.


### Part 4.4: Before and After Comparison

After removing training images that included my face, I retrained the model and tested the pen again. The results improved significantly. Before making changes, the model correctly recognized the pen in 3 out of 5 tests. After making changes, it correctly recognized the pen in all 5 tests.

The model's confidence also improved when the pen was shown from different angles and distances. This experiment showed me that the quality and content of training images can greatly affect how well an AI model performs. I learned that training images should focus on the actual object rather than unrelated details in the background.
