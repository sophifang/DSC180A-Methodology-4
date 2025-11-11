---
layout: default
title: DSC180A Methodology Assignment 4, Task 2
---

Sophia Fang ([sofang@ucsd.edu](mailto:sofang@ucsd.edu))\
Section B25 - Amitash Nanda

**1. What is the most interesting topic covered in your domain this quarter?**\
The most interesting topic covered in my domain this quarter was demand forecasting. This was the first time I had the opportunity to work on a time series project and the nature of the data and the tasks required be to approach each step of the data science lifecycle differently than before. For example, when it came to ML modelling, we needed to guarantee that we were always respecting temporal order throughout, which meant never sorting the data. Additionally, we opted for a walk-forward validation technique to train our model on an expanding window of past data for a model that can ideally adapt to changing patterns. This was particularly important for us because with a times series/demand forecasting project, future data should never be mixed into the training data. Other new techniques I practiced as a result of this topic included adding lag and moving average features to the dataset.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**\
For my Quarter 2 Project, I'd love to look more closely at abandoned calls. Because the work our team is doing with Erlang-C this quarter focuses on incoming calls—which is made up of both answered calls and abadoned calls—it operates under the assumption that callers wait indefinitely. In reality, the abandonment rate may change depending on various queue conditions as well as customer patience. This investigation could lead to the opportunity to practice new techniques and improve our staffing optimization.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**\
For our Quarter 1 Project, our team's current approach involves working independently on coding tasks in separate GitHub repositories and sharing our progress during our weekly section meetings. A potential change I'd love to make to this approach is to switch to working out of one GitHub repository for our Quarter 2 Project. I think this would be beneficial because it will give us more practice with version control and working with different branches. We could also practice reviewing each other's code through approving pull requests. The last benefit would be that this would allow our team to delegate tasks and move at a more efficient pace while staying on the same page about research findings and key insights.

**4. What other techniques would you be interested in using in your project?**\
So far, I've had the opportunity to learn a variety of ML modelling techniques via the demand forecasting and supply optimization phases of our Quarter 1 Project. As someone who is interested in pursuing more business-focused roles post-grad, I would love to create a public-facing "product"/interactive user interface at the end of the capstone that will allow users to interact with our model. For example, this [Erlang Calculator](https://www.callcentretools.com/tools/erlang-calculator/) is a website that returns the number of agents required on staff for a call center to reach a specific service level given user-populated fields. I would love to learn the web development techniques needed to implement a feature with similar functionality in our project.
