# I2 Intro Course Schedule

Note that this syllabus may evolve as we adapt the course to fit students' needs. Focus on one week at a time!

---

## Week 0: 1/3 - 1/8

### Purpose

- Get acquainted with I2
- Learn some of the pre-reqs necessary (Python)

### Resources

- [CS50x Intro to Python Course](https://cs50.harvard.edu/python/2022/). Doing the first lectures and psets would likely be enough to start off with.
- [CS231n notes on Python, Numpy, and Jupyter Notebooks](https://cs231n.github.io/python-numpy-tutorial/)

### Assignment

- N/A, get familiar with the pre-reqs!

### Summary Questions

- N/A

---

## Week 1: 1/9 - 1/15

### Purpose

- Get acquainted with I2
- Learn some of the pre-reqs necessary (calculus, linear algebra)

### Resources

- TODO: ADD CALCULUS AND LINEAR ALGEBRA RESOURCES, derivatives, partial derivatives, vectors, hyperplanes

### Assignment

- N/A, get familiar with the pre-reqs!

### Summary Questions

- N/A

---

## Week 2: 1/16 - 1/22

### Purpose

- Introduction to ML
- Introduction to Neural Networks

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1Sv8vHtzgqg4DMKjXRyvoRzjghlzFbDErwvN0DKh8yxk/edit?usp=sharing)
    - Unit 1
    - Unit 2
- [CS231n Notes on Neural Networks.](https://cs231n.github.io/) See Module 1: Neural Networks - great written resource for the basics.

### Assignment

- Complete Units 1 and 2 in the megadoc (synthesis questions included)
- Scikit-Learn ML Project (in megadoc/github)
- Basic MNIST Classifier (in megadoc/github)

### Summary Questions

- Synthesis questions in the megadoc

---

## Week 3: 1/23 - 1/29

### Purpose
Welcome to a beginner's introduction to neuroscience! We will

- Learn several basic regions of the brain
- Learn fundamentals of the neuron and biological computation
 -Begin to hypothesize about the parallels and divergences of machine learning and the brain

### Resources
- [I2 Resources Doc](https://docs.google.com/document/d/1Sv8vHtzgqg4DMKjXRyvoRzjghlzFbDErwvN0DKh8yxk/edit?usp=sharing)
    - Unit 3, Basic Neuroanatomy

### Assignment

- Complete Unit 3 in the megadoc (synthesis questions included)
- Basic Neuroanatomy Project (in megadoc)

### Summary Questions

- Synthesis questions in the megadoc

---

## Week 4: 1/30 - 2/5

### Purpose

- Review NN's
- Work through backpropagation

### Resources

- [Karpathy micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0) (simple version of backprop and how PyTorch autograd works). Watch this video (you're going to implement it!)
- [CS231n Notes - Backpropagation, Intuitions](https://cs231n.github.io/optimization-2/). Optional if you want review or a new explanation of backpropagation.

### Assignment

- Watch and implement micrograd. Starter code will be released later.
- Implement the ReLU nonlinearity for the Value class. (Note: if you're having a hard time with this, take a look at [this](https://github.com/karpathy/micrograd/blob/master/micrograd/engine.py) code.)
- Implement and train a small neural network using micrograd. The training, validation, and test data will be included in the starter code. - Try to find the best network you can! You might want to change the learning rate, size of the network, or Note your training, validation, and test loss for your best network.

### Summary Questions

- In what direction do gradients flow (with regards to loss)?
- How do gradients flow through addition? How do they flow through the ReLU function?
- What was your best loss for the test dataset?
- Was there something that stood out to you? Something that confused you?
- What's one resource that was helpful (suggested or found on your own)?

---

## Week 5: 2/6 - 2/12

### Purpose

- Deep Learning for Vision
- Learn about Convolutional Neural Networks

### Resources

- [CS231n Notes on CNNs](https://cs231n.github.io/convolutional-networks/)

### Assignment

- Train on a portion of imagenet? **not sure**

### Summary Questions

- What do CNN's do in terms of features?
- (If we did an assignment on imagenet), what was your maximum accuracy?
- What is "stride" for a convolutional layer?
- What is a pooling layer?
- What is "padding"?
- What's one resource that was helpful (suggested or found on your own)?

---

## Week 6: 2/13 - 2/19

### Purpose

This week we take a small break from computation and return to the brain, specifically your insanely complex and elegant visual system! We will  
- Learn the basic anatomical and functional regions of the visual system
- Compare biological solutions to visual tasks with computational solutions

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1Sv8vHtzgqg4DMKjXRyvoRzjghlzFbDErwvN0DKh8yxk/edit?usp=sharing)
    - Unit 4, Intro to the Visual System

### Assignment

- I don't really know

### Summary Questions

- I don't really know

---

## Week 7: 2/20 - 2/26

### Purpose

- Learn about language modeling and autoregressive models
- Get a basic idea about how Transformer models work
- Learn about fine-turning foundation models

### Resources

**These are suggested resources this week - feel free to use them all, skim them, or find others!**
- [The Annotated Transformer](http://nlp.seas.harvard.edu/annotated-transformer/) - the [Attention Is All You Need](https://arxiv.org/abs/1706.03762) paper annotated with PyTorch.
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) Another good explanation of Transformers.
- [NanoGPT](https://github.com/karpathy/nanoGPT), simple example code for a GPT model.
- [Blog posts](https://cswartout.com/2022/11/25/intutive-explanation-of-gpt.html) by Carter explaining GPT models (shameless plug).
- [Fine-tuning Huggingface models](https://www.youtube.com/watch?v=GSt00_-0ncQ). Basic guide on how to fine tune those models. Feel free to use this guide or others (I'll try to find other good ones).
- [I2 Resources Doc](https://docs.google.com/document/d/1Sv8vHtzgqg4DMKjXRyvoRzjghlzFbDErwvN0DKh8yxk/edit?usp=sharing)
    - Unit 12, Human Characteristics of the Brain
  
### Assignment

- Write a couple of sentences about foundation models, Transformers, or self-attention - your choice! Post it in the Discord!
- Fine-tune a GPT model from Huggingface to generate new Pokemon names! Instructions, dataset, and starter code will be released in the future.
- Bonus Assignment: Task 2 in Unit 12, Human Characteristics of the Brain

### Summary Questions

- What can transformers be used for?
- Describe (masked) self-attention.
- What are some examples of foundation models?
- What're your favorite generated Pokemon names?
- Was there something that stood out to you? Something that confused you?
- What's one resource that was helpful (suggested or found on your own)?

**not sure what else are good questions rn**

---

## Week 8: 2/27 - 3/5

### Purpose

- Go over basics of RL
- Learn about Deep Q Learning
- Learn about 

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1Sv8vHtzgqg4DMKjXRyvoRzjghlzFbDErwvN0DKh8yxk/edit?usp=sharing)
  - Unit 6, Reinforcement Learning
  - Unit 7, Intro to Movement
- [Spinning Up](https://spinningup.openai.com)

### Assignment

- TODO View megadoc (Varun wrote a bit about this I think)
- Complete Task 1 from Intro to Movement in the megadoc

### Summary Questions

- View megadoc (paste from megadoc)
- What's one resource that was helpful (suggested or found on your own)?

---

## Week 9: 3/6 - 3/12

### Purpose

- Even more Neuroscience!!!

### Resources
- [I2 Resources Doc](https://docs.google.com/document/d/1Sv8vHtzgqg4DMKjXRyvoRzjghlzFbDErwvN0DKh8yxk/edit?usp=sharing)
    - Unit 11, Building a Brain

### Assignment

- I don't really know

### Summary Questions

- I don't really know

---

## Week 10: 3/13 - 3/19

### Purpose

- Wrap up the quarter!

### Resources

- N/A

### Assignment

- N/A

### Summary Questions

- N/A

---

Please let me know if there's any changes you'd recommend! This is meant to help everyone - we want what's most effective.
