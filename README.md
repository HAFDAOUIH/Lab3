# Short Answer Grading Capstone Project

This repository contains a Jupyter Notebook for the Short Answer Grading Capstone Project. The project focuses on developing a model to automatically grade short answer responses. The dataset used in this project is sourced from [this CSV file](https://github.com/dbbrandt/short_answer_granding_capstone_project/blob/master/data/sag/answers.csv).

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Notebook Details](#notebook-details)
6. [Results](#results)
7. [Contributing](#contributing)

## Project Overview
The goal of this project is to develop a machine learning model capable of grading short answer questions. This involves natural language processing (NLP) techniques to understand and evaluate the textual responses against expected answers.

## Dataset
The dataset used in this project consists of student responses to various questions along with the corresponding grades. It is available in CSV format [here](https://github.com/dbbrandt/short_answer_granding_capstone_project/blob/master/data/sag/answers.csv). Each entry in the dataset includes:
- `id`: Identifier for the answer.
- `answer`: Text of the student's answer.
- `score`: The grade assigned to the answer.
- `correct`: Represent if the student asnwer with correct or not

## Installation
To run the notebook and reproduce the results, you need to have the following software and libraries installed:

- Python 3.7 or higher
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn

You can install the necessary libraries using pip:
```sh
pip install pandas numpy scikit-learn nltk matplotlib seaborn


## Usage
Clone the repository:
```sh
git clone https://github.com/HAFDAOUIH/short_answer_grading.git
