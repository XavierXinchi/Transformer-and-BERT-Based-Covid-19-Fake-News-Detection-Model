# README

During the past few years, the whole world has been swept by the Covid-19 epidemic, during which a lot of fake news appeared. Thus, we aimed to build a model which can quickly and efficiently identify misinformation about Covid-19 to combat the global infodemic.

The training dataset contains 8,560 data points collected from various online social networks such as Twitter, Facebook, and Instagram, etc.

Firstly, we improved the Covid-19 fake news classification system by fine-tuning the pre-trained BERT. Next, we integrated fine tuning BERT with and without frozen parameters and BiLSTM layers,  and achieved one of the SOTA(state-of-the-art) results on the fake news detection task, with an absolute improvement of 8.9% compared to the traditional machine learning baseline.

## File Explanation

- Data: the dataset of the fake news, containing training, validating and testing dataset.
- Code: The source Python code of the model.
- Presentation:  Project defense PPT.

