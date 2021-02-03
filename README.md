# Self-Driving Car

Developing a basic AI which learns to self drive a car. It is a very basic understanding of how an AI works and how it can be used to implement in self driving cars.

## Background
Being fascinated with AI, I read a lot about neural networks, reinforcement learning, experience replay and Deep-Q Learning intuition, implementation and visualization.
On going through different possible projects as a beginner, I came across this amazing topic to work on. Being Mechanical Engineer, I am fascinated with the concept of auto driving cars of Tesla and to feel the basic concepts applied on those cars I decided to make an AI for a built virtual environment in Kivy. 

## Directory Layout
```go
    +-- car.kv
    +-- map.py
    +-- ai.py
    +-- README.py
```
## Building an Environment
The environment for this is built on Kivy package. You can check the instructions for installing this package [here](https://kivy.org/doc/stable/gettingstarted/installation.html). The environment includes the car, the sand(which will be used to draw different obstacles and even a path for a road) and the three sensors in front of a car. In *map.py* these components are defined and this where the object **brain** of Dqn class in *ai.py* is initialized. 

                                                            ![Environment](./assets/environment.jpeg)

Note: I did not build this environment, I used an already coded built copy of this environment but was able to connect to my AI only with basic undeerstanding of the file. 

## WorkFlow Process
```go
    +-- Setting up Parameters
        +--This include defining angle, rotation, position, velocity of car and the three sensors individually.
    +-- Updating the relative distance of the goal from car
    +-- The Input States
        +-- The input layer consists of 5 neurons parameter.
    +-- The Ouptut Actions
        +-- Defining the output action as left, right or forward with the possibilty of exploration and exploitation.
    +-- The Rewards
    +-- Implementing Experience Replay
    +-- The Feedback
    +-- Procedure to Reset AI or Save AI.
```
## Final

                                                         ![Testcase](./assets/testcase1.jpeg)



