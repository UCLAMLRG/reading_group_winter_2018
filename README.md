# UCLA Astronomy Machine Learning Reading group - Winter 2018

## Goals
Machine learning is a topic that has risen in prominence recently as we get more and more data. We are seeing techniques from machine learning used more widely in astronomy. The goal of this reading group is to become more familiar with topics in machine learning and its connections to statistical tools that are in use in Astronomy. The plan is to go through a couple of textbooks on machine learning and discuss the basic underlying principles and methods. It would be in the style of a reading group where everyone would read the same topic, but a presenter would rotate each meeting and present a topic with associated code implementing the algorithm.

## Useful References
- Fundamentals of Machine Learning for Predictive Data Analytics - Kelleher, J.; Namee, B.; D'Arcy, A.
- Deep Learning by Goodfellow, I.; Bengio, Y.;  Courville, A.
  - website: http://www.deeplearningbook.org/
  - https://github.com/HFTrader/DeepLearningBook
- Python Data Science Handbook by VanderPlas, J.
  - website: https://github.com/jakevdp/PythonDataScienceHandbook
- Hands-On Machine Learning with Scikit-Learn and TensorFlow
  - Safari Books Online: http://proquest.safaribooksonline.com/book/programming/9781491962282
  - github page: https://github.com/ageron/handson-ml
- Machine Learning: A Probabilistic Perspective - Kevin P. Murphy
- Data Analysis: A Bayesian Tutorial - Sivia, D. & Skilling, J. - Not part of regular reading, but this is a useful reference for Bayesian statistics

## Quick-Getting started with SciServer Compute
SciServer.org is a computational cloud environment that Johns Hopkins University (IDIES group) has generously allowed us to use for our projects. Jupyter notebooks/terminal are the interfaces to access datasets such as SDSS. Here's how to clone this github repo into your SciServer account:
1. Create an account at sciserver.org and go to Compute
2. Create a new container (Docker container), choose the type to be Python, and a container Jupyter notebook interface will be created.
3. On the right hand side, go to New-> terminal and a black terminal interface will appear.
4. In this order in the terminal, type each of these at a time (separated by a comma) and hit enter:
5. ls, cd home, ls, cd idies, cd workspace, cd persistent, ls, git clone url-of-git-repository-here
6. the repository will now be in your folder.


## Code Samples
-- SciServer cosmology and astronomy Jupyter Notebook code samples https://github.com/sciserver/Notebooks


## Schedule
Meetings will take place on Fridays at 11 am to Noon in **PAB-3-703**. Room changes will be sent via email.

**Organizers**: Tuan Do ([@followthesheep](https://github.com/followthesheep)), Bernie Randles ([@brandles](https://github.com/brandles))

| Date | Topic | Readings | Presenter |
| --- | --- | --- | --- |
|2018-01-26 | Fairness in Machine Learning  | [Week 1 Readings](week1/README.md)  | T. Do|
|2018-02-02 | Generative Adversarial Networks  | [Week 2 Readings](week2/README.md)  | T. Do     |
|2018-03-02 | ML and Gerrymandering | [Week 3 Readings](week3/README.md)   | B. Boscoe     |
|2018-03-09 | Light curve classification | [Week 4 Readings](week4/README.md)  |   A. Gautam   |
|2018-03-16 | Hierarchical spectral clustering & DNA Phenotyping | [Week 5 Readings](week5/README.md) |I. Pasquetto  |
|2018-03-21 | ML and exoplanets | [Week 6 Readings](week6/README.md) |J. Zink | 
