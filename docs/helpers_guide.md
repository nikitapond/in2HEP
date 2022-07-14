<h2 align = 'center'> In2Science Activity Week 25/07/2022 - 29/07/2022</h2>

**Overview of the event.**

The aim of the week is to introduce students with an interest in STEM to data science techniques. The week consists of an initial introduction day, in which students shall be taught the basics of python and jupyter notebooks. We shall then introduce machine learning in a notebook which guides students through the process of setting up and training a simple model which aims to classify the hand-written digits of the MNIST dataset. On Wednesday and Thursday, the students shall be introduced to the task of discerning Higgs boson decays from background events, initially using a 'cut-based' approach, in which dataframes are directly modified, followed by a nerual network approach. On the Friday, the students shall prepare and present a ~5 minute presentation on the work they achieved, with a small prize being given to the winner.

Each of the first 4 days has an associated jupyter-notebook that the students shall work through and modify. They are summarised below:

* [Python Crash Course](../notebooks/Python&#32;Crash&#32;Course&#32;.ipynb) - A notebook which introduces python, assuming no prior knowledge, including basics such as print statements, variables, lists, dictionary, and writing functions. The notebook also includes a range of exercises for the students to attempt.

* [MNIST](./notebooks/MNIST.ipynb) - A notebook which provides a basic NN that classifies the MNIST digits, as well as a CNN. Students shall be asked only to edit the final model, with the aim of increasing accuracy, without needing to understand how we load/prepare data.

* [Python Crash Course](./notebooks/ATLAS&#32;Cut&#32;Based&#32;.ipynb) - A notebook which introduces the Higg -> bb decay. Data is loaded into a Pandas data frame, and students will aim to increase the sensitivity of the measurement by manually applying 'cuts' that aim to remove background events, and maximise signal events.

* [Python Crash Course](./notebooks/ATLAS_NN.ipynb) - A notebook which introduces a neural network to the task of discerning signal from background events. Data preparation is provided, and the students shall only be expected to edit the models, creating plots showing change in sensitivity as certain model parameters are changed. Making of plots should be encouraged, as they will be useful for the presentations on Friday.

**Teaching Methods and Pedagogy**

We would like to encourage more young people from disadvantaged background to engage with physics. Crucial to this is to remember that not everyone will have had the same amount of exposure to physics or science generally. Not everyone will feel as comfortable asking questions and some students, especially female students, may not feel as confident in the groups. Our goal is to ensure they learn the material whilst addressing some of these issues that inhibit learning.

* Regularly check if they understand what is going on. There is a very good ratio on the day so this will be fairly easy.

* Explain the problem and solution in simple terms/language and avoid jargon. This one is difficult because there are a lot of words that you will use regularly as a PhD student and are second nature to you but these students are only just hearing them for the first time.

* Although there is a competition in the event, the aim is to introduce them to AI and physics. So if your group learns loads about what you do, how neural networks work, and how we use machine learning in tech/society/science, that is a better outcome than if they win the prize. 