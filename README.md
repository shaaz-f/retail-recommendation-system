# retail-recommendation-system

This project implements a product recommendation system using PyTorch. The goal is to train a model that can recommend relevant products to users based on their past behavior, including clicks, cart additions, and purchases.

I am using Neural Collaborative Filtering in order to learn nonlinear relationships while also understanding the ins and outs of PyTorch.

## Features
Literally just preprocessing, building, training, and using the model for predictions. Also evaluation metrics.

## Dataset
https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset/data

## Tech Stack
- Python 3
- VSCode
- PyTorch, pandas, numpy, scikit-learn
- Jupyter Notebook

## The Process
- The goal of this project was primarily to learn PyTorch in a more interactive way, as I have not used it to it's fullest up to this point (mostly boilerplate code).
- I didn't want the project itself to be too easy, and so I decided to implement something I haven't even learned the theory about up to this point in recommendation systems.
- At the end, I wanted to implement a Neural Collaborative Filtering model to make use of neural networks in recommender systems.
- I ran into many problems including simple overfitting but also just not knowing what I was doing, but through a few resources and some trial and error, I was able to figure it out.

*Keep in mind, there is always room for improvement, but I consider this a success given my new found understanding of PyTorch*

## How to use
1. Pull the git or download the files.
2. Download the dataset to the same directory under data/
3. Pip install the requirements.txt to your env.
4. Run the notebook.

## What's next?
- Fix up the evaluations.
- Log more stuff.
- Spend some time fine-tuning hyperparameters for better convergence.

## References
- https://arxiv.org/abs/1708.05031
- https://github.com/yihong-chen/neural-collaborative-filtering/tree/master
- https://youtu.be/O4lk9Lw7lS0?si=T4tDJ1xz1I9IuCvv

