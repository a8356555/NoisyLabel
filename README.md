Experimenting on 

https://colab.research.google.com/drive/1yNLT6kJxTY5LNwaVebQGtFv1MElg8jaf#scrollTo=n49IjYULos6a

# Table of Contents
* [Noisy Label Skills & Papers](#nls)
    1. [Dataset info](#di)
    2. [Target](#ta)
    3. [Papers](#p)
    4. [Experiment](#ex)
    5. [TODO](#todo)

# <a name="nls">Noisy Label Skills & Papers    
## <a name="di">Dataset info
* label noise rate around 12%
    
## <a name="ta">Target
* Find an approach effective at finding out errors.
* Find an framework that can build robust models having better performance without manually adjusting the labels.
* Training on hard samples.
    
## <a name="p">Papers
* see paper_note.txt
    
## <a name="ex">Experiment
* Use easy binary classification model to detect blank pictures.
* Use Confusion Matrix to find hard samples and data with noisy labels.
* Use softmax confidence score to find out error: can find around 70% errors.
* Use Noisy-Student to further improve the model robustness.
* 1-stage 懶人法: ^w_t = a*w_{t-1} + (1-a)*w_{t} 
* (Loss Function)
    
## <a name="todo">TODO
* Implementation of approaches of other papers
