# Arabic Sentiment Analysis for Hotel Reviews

## Introduction

This project is part of a university end-of-year project.

We're building a model that allows us to classify arabic reviews according to their aspect (Food Quality, room quality, hotel service, etc...)

It is currently a work in progress. And we're planning to fine-tune it in the upcoming period.

The building of the model and training is made through the Pytorch Lightning Framework (as it's more object-ortiented like python).

It's using a custom made pre-processing:
- Word Stemming
- Removal of non arabic letters
- Removal of repeated letters
- Replacement of emojis with corresponding arabic meaning
- Whitespace Removal
- Kashida (or tatweel) removal
- etc...

Finally, the optimization is with AdamW algorithm as it gives the best results (the results are close to the normal Adam algorithm).

For the evaluation, we're still testing it right now but as a multi-label classification we can take the micro average f1 score as the best metric for this model.

## How to run

You have to add [this Google Drive Folder](https://drive.google.com/drive/folders/1b37oipo4ZC7MrZuHHBBg7OUM-9hvTd2j?usp=sharing) as a shortcut in your own Drive

Then open the [Colab Notebook](https://colab.research.google.com/github/YoussefJJ/arabic-sentiment-analysis-for-hotel-reviews/blob/main/multi_label.ipynb) and run the desired cells.

## Contributors

Contributing to this project are [Youssef Jerbi](https://github.com/YoussefJJ), [Maryem El Ajlani](https://github.com/MeryamAjlani) and [Aymen Boujmil](https://github.com/AymenBoujmil)
