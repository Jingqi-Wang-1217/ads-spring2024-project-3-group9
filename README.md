# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2024

+ Team 9
+ Team members
	+ Yu, Yang
	+ Wang, Jingqi
	+ Lee, Rhoan
	+ Zhou, Jitian

+ Project summary: This project entails developing and evaluating models for image classification within a dataset characterized by both noisy and clean labels. Initially, a baseline model using logistic regression on RGB histogram features is established. Subsequently, two convolutional neural network (CNN) models are introduced: Model I, trained on noisy labels, and Model II, trained on corrected labels to mitigate the impact of noise. Performance evaluation of these models on a clean-labeled test set reveals the superiority of CNNs over the baseline in handling image data, particularly when trained on corrected labels. The project underscores the importance of label quality and the effectiveness of deep learning in complex pattern recognition, balancing accuracy with computational efficiency in model selection. 
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
