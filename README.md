[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/FQjqq_wh)
# Project title: ReadMeNext ({2024}-{Spring} 23/04)

* Team members: Ahmad Diab (ahmad.diab@pitt.edu), Mohammad Hajjaj (moh33@pitt.edu)
* Project presentation: https://github.com/class-data-mining-master/2024-spring-dm-project-2024-spring-team-2-readmenext/blob/1751a7b593acd5716400ba28ff2016349ce1bf2f/ReadMeNext_slides.pdf
* Project paper: https://github.com/class-data-mining-master/2024-spring-dm-project-2024-spring-team-2-readmenext/blob/1751a7b593acd5716400ba28ff2016349ce1bf2f/ReadMeNext_final_paper.pdf


## Description
Technological advancements have revolutionized human life, offering benefits such as internet connectivity, global access to diverse content, and unprecedented opportunities for engagement. However, this abundance of information, coupled with the fast pace of modern life, presents a pressing challenge: how to effectively select what to consume amidst the deluge of options available. In this project, we address the longstanding issue of book recommendation within the context of the contemporary era, characterized by the proliferation of Large Language Models (LLMs). While existing research has primarily focused on leveraging metadata such as book attributes, publisher information, and author profiles, we harness the power of LLMs —specifically, RoBERTa Large Model — and incorporate insights derived from user-generated content (i.e. review texts), to enhance the recommendation process. Our novel system, "ReadMeNext," employs a suite of machine learning algorithms including glmnet, KNN, Decision Tree, Random Forest, Naive Bayes, and SVM, to achieve commendable performance, as observed by an F1 score of 0.83, comparable to established models in the literature.
Summary for the major directories and files: 
* Full code (implemented in R): **Final_Project.Rmd** (https://github.com/class-data-mining-master/2024-spring-dm-project-2024-spring-team-2-readmenext/blob/be886dfaec2467fce7a0bd75b09cc310824cc613/Final_Project.Rmd)
* Project presentation Slides: **ReadMeNext_slides.pdf** (https://github.com/class-data-mining-master/2024-spring-dm-project-2024-spring-team-2-readmenext/blob/1751a7b593acd5716400ba28ff2016349ce1bf2f/ReadMeNext_slides.pdf)
* Project report (paper): **ReadMeNext_final_paper.pdf** (https://github.com/class-data-mining-master/2024-spring-dm-project-2024-spring-team-2-readmenext/blob/1751a7b593acd5716400ba28ff2016349ce1bf2f/ReadMeNext_final_paper.pdf)
* Progress Report: **progress-report-final.Rmd** (https://github.com/class-data-mining-master/2024-spring-dm-project-2024-spring-team-2-readmenext/blob/1751a7b593acd5716400ba28ff2016349ce1bf2f/progress-report-final.Rmd)

## Prerequisites
The project is implemented using R. The list of the required packages are: ggplot2, ggplot, tidyverse, rsample,
tidymodels, caret, nnet, part, randomForest, pROC, caretEnsemble, VIP, lubridate, tm, quanteda, wordcloud, RColorBrewer, naniar, themis

## Authors
Ahmad Diab (ahmad.diab@pitt.edu) and Mohammad Hajjaj (moh33@pitt.edu)

## Acknowledgments
We wish to express our gratitude to Professor Yuru Lin for her invaluable support and guidance throughout our Data Mining course. Her expertise and encouragement were instrumental in shaping this project. Thank you, Professor Lin, for your unwavering commitment to our academic journey.

### Inspiration
All the code used for this project was written from scratch by authors. Parts of the code were inspired by Homework-3 assigned in this class, Data Mining, which was implemented by the authors.

## License
[MIT](https://choosealicense.com/licenses/mit/)
