# KNN-from-scratch-in-python
Understanding and creating KNN
# KNN From Scratch – No Libraries, Just Vibes

Hey !   
I did everything in a **Google Colab notebook**, so you can follow along easily and see how the code works step by step.

---

## Check it out here:
[📎 Click to open the notebook]([https://colab.research.google.com/drive/1NwiMijVrLzxDd4NQQ31qQxjqYE-elloH?usp=drive_link])


## What’s inside?
- A custom `KNearestNeighbors` class
- `fit()` and `predict()` methods
- Tested with some 3D points (because 2D is too mainstream :)))

---

## Fun fact:
If we set `k = 11` and add a new point far away like `[10, 10]`,  
it will be classified as **red** – even if it's not that close.  
Why? Because KNN cares about the **majority of neighbors**,  
**not how close** they are. Democracy wins. 

---



