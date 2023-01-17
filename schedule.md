# I2 Intro Course Schedule

Note that this syllabus may evolve as we adapt the course to fit students' needs. Focus on one week at a time!

---

## Week 0: 1/6 - 1/13

### Purpose

- Get acquainted with I2
- Learn some of the pre-reqs necessary (Python)

### Resources

- [CS50x Intro to Python Course](https://cs50.harvard.edu/python/2022/)
- [CS231n notes on Python, Numpy, and Jupyter Notebooks](https://cs231n.github.io/python-numpy-tutorial/)

### Assignment

- Complete units in the CS50x Intro to Python Course **as needed** (If you are confident, feel free to skip a section). I reccomend:
    - 0: Functions, Variables
    - 1: Conditionals
    - 2: Loops
    - 4: Libraries
    - 9: Et Cetera
- Read through CS231n Notes, focusing on:
    - Containers
    - Numpy
    - MatPlotLib

### Summary Questions

- N/A

---

## Week 1: 1/13 - 1/20

### Purpose

- Get acquainted with I2
- Learn some of the pre-reqs necessary (calculus, linear algebra)

### Resources

- [Linear Algebra Review and Reference](https://www.cs.cmu.edu/~zkolter/course/linalg/linalg_notes.pdf) (Just Unit 1)
- [Vector Basics](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=1)
- [Hyperplane Definition](https://deepai.org/machine-learning-glossary-and-terms/hyperplane)
- [Hyperplane Math](https://www.youtube.com/watch?v=xNSR9p9XLt8)
- [Partial Derivatives (Mathematical)](https://www.youtube.com/watch?v=AXqhWeUEtQU)
- [Partial Derivatives (Graphical)](https://www.youtube.com/watch?v=dfvnCHqzK54)

### Assignment

- Read/Watch provided resources to learn/refresh your math knowledge. 
- If you are already familiar with the concepts listed above, feel free to skip them. I would, however, reccomend you explore linear algebra in high dimensional spaces (specifically **hyperplanes**) and revisit **partial derivatives**.

### Summary Questions

- Define a hyperplane in a way that helps you understand it conceptually

---

## Week 2: 1/20 - 1/27

### Purpose

An introduction to the foundation of modern AI!
- Introduction to Machine Learning (ML)
- Math behind Linear Regression, SVM, PCA
- Basic Unsupervised Clustering

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
    - Unit 1

### Assignment

- Complete Unit 1 in the megadoc (synthesis questions included)
- Scikit-Learn ML Project (in megadoc/github)

### Summary Questions

- Synthesis questions in the megadoc

---

## Week 3: 1/27 - 2/3

### Purpose

Our first foray into more complex networks and how they learn.
- Introduction to Deep Learning (DL)
- Introduction to Neural Networks
- Introduction to Backpropagation

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
    - Unit 2
- [CS231n Notes on Neural Networks.](https://cs231n.github.io/) See Module 1: Neural Networks - great written resource for the basics.

### Assignment

- Complete Unit 2 in the megadoc (synthesis questions included)
- Basic MNIST Classifier (in megadoc/github)

### Summary Questions

- Synthesis questions in the megadoc

---

## Week 4: 2/3 - 2/10

### Purpose

Welcome to a beginner's introduction to neuroscience! We will
- Learn several basic regions of the brain
- Learn fundamentals of the neuron and biological computation
 -Begin to hypothesize about the parallels and divergences of machine learning and the brain

### Resources
- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
    - Unit 3, Basic Neuroanatomy

### Assignment

- Complete Unit 3 in the megadoc (synthesis questions included)
- Basic Neuroanatomy Project (in megadoc)

### Summary Questions

- Synthesis questions in the megadoc

---

## Week 5: 2/10 - 2/17

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

## Week 6: 2/17 - 2/24

### Purpose

- Deep Learning for Vision
- Learn about Convolutional Neural Networks

### Resources

- [CS231n Notes on CNNs](https://cs231n.github.io/convolutional-networks/)

### Assignment

- Train on a portion of imagenet

### Summary Questions

- What do CNN's do in terms of features?
- (If we did an assignment on imagenet), what was your maximum accuracy?
- What is "stride" for a convolutional layer?
- What is a pooling layer?
- What is "padding"?
- What's one resource that was helpful (suggested or found on your own)?

---

## Week 7: 2/24 - 3/3

### Purpose

This week we take a small break from computation and return to the brain, specifically your insanely complex and elegant visual system! 
We will  
- Learn the basic anatomical and functional regions of the visual system
- Compare biological solutions to visual tasks with computational solutions

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
    - Unit 4, Intro to the Visual System

### Assignment

- Complete the project in Unit 4 in the megadoc
- Remember to bring your creation to the meeting on Friday!

### Summary Questions

- Synthesis questions in the megadoc

---

## Week 8: 3/3 - 3/10

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
- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
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

---

## Week 9: 3/10 - 3/17

### Purpose

- Go over basics of RL
- Learn about Deep Q Learning
- Learn about movement in the context of the brain

### Resources

- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
  - Unit 6, Reinforcement Learning
  - Unit 7, Intro to Movement
- [Spinning Up](https://spinningup.openai.com)

### Assignment

- Complete Task 1 from Intro to Movement in the megadoc

### Summary Questions

- Synthesis questions in the megadoc
- What's one resource that was helpful (suggested or found on your own)?

---

## Week 10: 3/17 - 3/24

### Purpose

This week, we're applying our knowledge. You're building a brain!
- Understand the connectivity of the brain
- Compare with the connectivity of analogous computation systems
- Creatively improvise on existing methods of creating intelligent systems

### Resources
- [I2 Resources Doc](https://docs.google.com/document/d/1y4t664jcL88Vnwwm_EoTnQF1t2_4IAKEIMh9i7wtzIg/edit?usp=sharing)
    - Unit 11, Building a Brain

### Assignment

- Complete Unit 11 in the megadoc (synthesis questions included)
- Basic Neuroanatomy Project (in megadoc)

### Summary Questions

- Synthesis Questions in the megadoc

---


Please let me know if there's any changes you'd recommend! This is meant to help everyone - we want what's most effective.
