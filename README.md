# Machine Learning

This public repository contains the shared course materials for students and the instructor, based on *Machine Learning with PyTorch and Scikit-Learn: Develop Machine Learning and Deep Learning Models with Python*. Each chapter uses one notebook for reading, teaching, and discussion.

## Course objective

This course introduces the foundations of machine learning and guides students in using Python, NumPy, pandas, and scikit-learn to prepare data, train models, and evaluate results. Students learn to explain the mathematical and computational logic of a model, recognize data leakage and model limitations, and complete a reproducible individual project. Students may use AI or other tools, but they remain responsible for understanding and defending their code, models, and conclusions.

## Course content

The course follows Chapters 1–10 of *Machine Learning with PyTorch and Scikit-Learn*. It covers machine learning foundations, classification, data preprocessing, dimensionality reduction, model evaluation and tuning, ensemble learning, sentiment analysis, regression, and clustering. Concepts and mathematical reasoning are connected to executable examples and result interpretation, then integrated through individual midterm and final project reports.

Students read the chapter materials independently, predict results before running code, interpret figures and tables, and discuss evidence in groups. They compare the reasoning behind different groups' responses rather than simply checking whether the conclusions agree.

From the first model-building exercises in Chapters 2–4, students learn the roles of training, validation, and test data. Preprocessing parameters are fitted using only the training data for the corresponding evaluation; validation data guide model choices, while the reserved test set is excluded from those choices. Chapter 6 develops these foundations into cross-validation, model evaluation, and hyperparameter optimization.

## Weekly outline

| Week | Chapter and direction |
|---:|---|
| 1 | Introduction; Chapter 1: Machine Learning Foundations |
| 2 | Chapter 2 I: Perceptron Learning |
| 3 | Chapter 2 II: Adaline and Gradient Descent |
| 4 | Chapter 3 I: Logistic Regression and Support Vector Machines |
| 5 | Chapter 3 II: Kernel SVM, Decision Trees, and Nearest Neighbors |
| 6 | Written Examination 1: Chapters 1-3 |
| 7 | Chapter 4: Data Preprocessing |
| 8 | Chapter 5: Dimensionality Reduction |
| 9 | No class: INFORMS Conference |
| 10 | Individual Midterm Project Report |
| 11 | Chapter 6 I: Model Evaluation |
| 12 | Chapter 6 II: Hyperparameter Optimization |
| 13 | Chapter 7: Ensemble Learning |
| 14 | Chapter 8: Sentiment Analysis |
| 15 | Chapter 9: Regression Analysis |
| 16 | Chapter 10: Clustering Analysis |
| 17 | Written Examination 2: Chapters 4-10; Final Evidence Check |
| 18 | Individual Final Project Report |

The weekly outline is a reference schedule and may be adjusted to course progress. Materials remain organized as complete chapters rather than fixed weekly units. Material not completed in class may be continued independently.

## Chapter materials

| Chapter | Course notebook |
|---:|---|
| 1 | [Giving Computers the Ability to Learn from Data](course/ch01main.ipynb) |
| 2 | [Training Machine Learning Algorithms for Classification](course/ch02main.ipynb) |

Additional chapter notebooks will be added after review.

## Assessment

| Component | Weight |
|---|---:|
| In-class work and ongoing learning evidence | 10% |
| Written Examination 1 | 15% |
| Written Examination 2 | 15% |
| Individual Midterm Project Report | 25% |
| Individual Final Project Report | 35% |
| **Total** | **100%** |

The written examinations verify each student's understanding of shared machine learning concepts, mathematical relationships, code behavior, and output interpretation. Written Examination 2 uses selected cross-chapter problems rather than attempting to test every subsection of Chapters 4–10 by recall.

The midterm report presents the problem, data, features, target, data split, visible preprocessing, a simple executable baseline, initial results, limitations, and a plan for later validation. Initial results use training and validation data, with their roles clearly identified. The reserved test set is not used to revise preprocessing, select models, or tune hyperparameters. A completed hyperparameter search or final model-selection procedure is not required before Chapter 6 is taught.

The final report adds the complete validation design, model comparison, error analysis, reproducibility evidence, and an individual explanation or operation check. Final test evaluation takes place after preprocessing choices, model selection, and hyperparameters have been fixed; its results are reported without using the same test set to guide further model development.

Lines of code, number of models, report length, number of prompts, and number of AI tools do not directly determine a grade.

## Textbook

Sebastian Raschka, Yuxi (Hayden) Liu, and Vahid Mirjalili, *Machine Learning with PyTorch and Scikit-Learn: Develop Machine Learning and Deep Learning Models with Python*, Packt Publishing, 2022.

Official code: <https://github.com/rasbt/machine-learning-book>

## Repository boundary

This repository contains reviewed course materials shared by students and the instructor. Textbooks, internal maintenance records, builders, validators, audits, solutions, unreleased assessments, and student records are maintained locally and are not published here.
