# Machine Learning

ML offers a new way to solve problems, answer complex questions, and create new content. ML can predict the weather, estimate travel times, recommend songs, auto-complete sentences, summarize articles, and generate never-seen-before images.

In basic terms, ML is the process of training a piece of software, called a model, to make useful predictions or generate content (like text, images, audio, or video) from data.

For example, suppose we wanted to create an app to predict rainfall. We could use either a traditional approach or an ML approach. Using a traditional approach, we'd create a physics-based representation of the Earth's atmosphere and surface, computing massive amounts of fluid dynamics equations. This is incredibly difficult.

Using an ML approach, we would give an ML model enormous amounts of weather data until the ML model eventually learned the mathematical relationship between weather patterns that produce differing amounts of rain. We would then give the model the current weather data, and it would predict the amount of rain.

## Supervised Learning

In machine learning, supervised learning (SL) is a type of machine learning paradigm where an algorithm learns to map input data to a specific output based on example input-output pairs. This process involves training a statistical model using labeled data, meaning each piece of input data is provided with the correct output. For instance, if you want a model to identify cats in images, supervised learning would involve feeding it many images of cats (inputs) that are explicitly labeled "cat" (outputs).

These ML systems are "supervised" in the sense that a human gives the ML system data with the known correct results.

The goal of supervised learning is for the trained model to accurately predict the output for new, unseen data. This requires the algorithm to effectively generalize from the training examples, a quality measured by its generalization error. Supervised learning is commonly used for tasks like classification (predicting a category, e.g., spam or not spam) and regression (predicting a continuous value, e.g., house prices).

### Regression

A regression model predicts a numeric value. A weather model that predicts the amount of rain in inches or millimeters, is regression model.

| Scenario           | Input Data                                                       | Numeric Prediction                |
| ------------------ | ---------------------------------------------------------------- | --------------------------------- |
| Future House Price | Square footage, zip code, # BR, # baths, lot size, interest rate | Price of home                     |
| Future Ride Time   | Traffic, distance, weather                                       | HH:MM:SS to arrive at destination |

---

### Classification

Classification models predict the likelihood that something belongs to a category. Unlike regression models, whose output is a number, classification models output a value that states whether or not something belongs to a particular category. For example, classification models are used to predict if an email is spam or if a photo contains a cat.

#### Binary Classification

Binary classification models output a value from a class that contains only two values, for example, a model that outputs either `rain` or `no rain`.

Multiclass classification models output a value from a class that contains more than two values, for example, a model that can output either `rain`, `hail`, `snow`, or `sleet`.

### Generalization

Generalization is the concept that humans, other animals, and artificial neural networks use past learning in present situations of learning if the conditions in the situations are regarded as similar. The learner uses generalized patterns, principles, and other similarities between past experiences and novel experiences to more efficiently navigate the world

## Unsupervised Learning

An unsupervised learning model aims to identify meaningful patterns in a dataset. For example, many unsupervised learning models rely on a technique called clustering to organize similar data into groups ("clusters").

Clustering differs from classification because the categories aren't defined by you. For example, an unsupervised model might cluster a weather dataset based on temperature, revealing segmentations that define the seasons. You might then attempt to name those clusters based on your understanding of the dataset.

![alt text](./images/image-1.png)

> ML model clustering weather patterns

## Reinforcement Learning

Reinforcement learning models make predictions by getting rewards or penalties based on actions performed within an environment. A reinforcement learning system generates a policy that defines the best strategy for getting the most rewards.

Reinforcement learning is used to train robots to perform tasks, like walking around a room, and software programs like [AlphaGo](https://deepmind.google/research/alphago/)to play the game of Go.

![alt text](./images/image-2.png)

## Generative AI

Generative AI can take a variety of inputs and create a variety of outputs, like text, images, audio, and video. It can also take and create combinations of these. For example, a model can take an image as input and create an image and text as output, or take an image and text as input and create a video as output.

We can discuss generative models by their inputs and outputs, typically written as "type of input"-to-"type of output." For example, the following is a partial list of some inputs and outputs for generative models:

- Text-to-text
- Text-to-image
- Text-to-video
- Text-to-code
- Text-to-speech
- Image and text-to-image

_How does generative AI work?_ At a high-level, generative models learn patterns in data with the goal to produce new but similar data. Generative models are like the following:

- Comedians who learn to imitate others by observing people's behaviors and style of speaking
  ![alt text](./images/carvey.png)
- Artists who learn to paint in a particular style by studying lots of paintings in that style

- Cover bands that learn to sound like a specific music group by listening to lots of music by that group
  <!-- markdownlint-disable-next-line MD033 -->
    <img alt="struts" src="./images/struts.png" width="25%">
- To produce unique and creative outputs, generative models are initially trained using an unsupervised approach, where the model learns to mimic the data it's trained on. The model is sometimes trained further using supervised or reinforcement learning on specific data related to tasks the model might be asked to perform, for example, summarize an article or edit a photo.

Generative AI is a quickly evolving technology with new use cases constantly being discovered. For example, generative models are helping businesses refine their ecommerce product images by automatically removing distracting backgrounds or improving the quality of low-resolution images.

---

> Sources

- [Google](https://developers.google.com/machine-learning/intro-to-ml/what-is-ml)
- [Wiki](https://en.wikipedia.org/wiki/Supervised_learning)
- [Hurricane Models](https://storm.aoml.noaa.gov/viewer/)
