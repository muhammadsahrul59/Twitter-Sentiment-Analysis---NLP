# Twitter Sentiment Analysis - NLP with LSTM for Multiclass Text Classification✨

## About Dataset
### Overview
This is an entity-level sentiment analysis dataset of twitter. Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral.

You can download Dataset in Kaggle : [Twitter Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis/data)

## Project Description
Welcome to the Natural Language Processing (NLP) project, employing Long Short-Term Memory (LSTM) for robust multiclass text classification. This project adheres to specific criteria, delivering a powerful solution for understanding and categorizing textual data.

## Key Features
- **Sequential Model Architecture**: The model is intricately designed sequentially for optimal data flow.
- **LSTM Utilization**: Harnesses the power of LSTM to capture intricate temporal patterns and relationships within the textual data.
- **Embedding Layer**: Employs the Embedding layer to represent words in a continuous vector space.
- **Tokenizer Function**: Utilizes a tokenizer function to convert text into sequences of tokens, making it compatible with the model.
- **20% Validation Set**: Allocates a 20% validation set from the total dataset for precise performance measurement during training.
- **Accuracy Exceeding 90%**: The model boasts accuracy exceeding 90% on both training and validation sets.
- **Classes and Data Samples**: The dataset encompasses 4 classes with a total of 3000 samples, enabling accurate multiclass classification.

## Run Google Colab
```
- Download the file above
- open https://colab.research.google.com/
- Upload the file Twitter_Sentiment_NLP.ipynb
```
or you can open it with this Google Colab Link below :

[![](https://img.shields.io/badge/Google%20colab-Open-FFC000.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAB8lBMVEUAAAD/7QL/6w7/6gz/6w3/6Qj/6Qj/6wj/6gf/6w//6w7/6xP/7gP/2hr/2xX/2jD/z0j/uHX/1zn/3Sz/3Sv/1zn/r4L/zE3/2jL/4ST/4Cf/0RP//zH/3S//2jL/2jL/2zH/3iv/3in/2zD/2jL/2jL/3C///0b/1B3/yxL/xAj/0SH/2DT/2TX/2TX/3C7/2jP/2DX/2DX/2DX/1zD/zRb/YwD/wgf/wQf/xAr/1iX/3C//3C//2zH/2Db/2jP/3C7/2zD/zBf/wgj/wgf/wgf/wQf/wQf/0ST/2y7/5B3/2TT/2TT/3iv/2y//zSD/wQb/wQf/wgf/wgf/wQf/wQf/zx7/3Cz/4x//2TT/2TX/4TD/zRb/wQf/wgf/wQf/wgf/wgf/wQf/wwr/1iT/3S//3C7/2zH/1zH/zBb/wQT/wgf/wQf/wQf/wgf//4r/xAj/0CD/2DT/2TX/2TX/3C7/zBb/wgj/wQf/wQf/wQf/wgf/xgf/0BL/6Rz/3C//2jL/2jP/2zH/3iz/vwD/wgf/wgf/wgf/wgf/xAf/wgf/2Rr/2hf/2TH/t3f//wD/1D//3S7/wgX/wAf/0wj/uQf/wQf/wwf/wgf/5gX/5h//6BT/5xb/6Q//6RD/xAf/xAf/xQf/xAf/xQf/xAf///9tAmifAAAApXRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAATiFmGgWFGaZi0EDAABa6v/5+32y//r/8WoBJ9viYD9wnv+kPlvc5TRg/XsAAArH4yEAAGz+cmL9dgAACsjhHgAAZ/50LOHcUzRbm/+VLUjT6TcAZvH89Pd5uv/x+fRxAgADRJSldRsYcKOVSAQAAAAAAAEAAAAAAQAAAAAAAAAAAAAAAAAAAABydb0CAAAAAWJLR0SlLrlKLwAAAAd0SU1FB+QIEQUaC7jgabcAAAABb3JOVAHPoneaAAAAwUlEQVQI12NgQAOMTMwsrGzsHJxc3DwMDLx8/AKCQsIiomLiEpJSDNIysnLyCopKyiqqauoaDJpa2jq6evoGhkbGJqZmDOYWllbWNrZ29g6OTs4uDK5u7h6eXt4+vn7+AYFBDMEhoWHhEZFR0TGxcfEJDIlJySmpaekZmVnZObl5DPkFhUXFJaVl5RWVVdU1DLV19Q2NTc0trW3tHZ1dDN09vX39EyZOmjxl6rTpMxgYZs6aPWfuvPkLFi5avATdAwCl1jTbaxUL4wAAAF5lWElmSUkqAAgAAAADABIBAwABAAAAAQAAADEBAgANAAAAMgAAAGmHBAABAAAAQAAAAAAAAABQaG90b3MgMi43LjAAAAIAAqAJAAEAAADTAAAAA6AJAAEAAADTAAAAAAAAAJOs9JgAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMTdUMDU6MjY6MTErMDA6MDBd4jn+AAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTE3VDA1OjI2OjExKzAwOjAwLL+BQgAAABh0RVh0ZXhpZjpFeGlmSW1hZ2VMZW5ndGgAMjExdjfLjwAAABd0RVh0ZXhpZjpFeGlmSW1hZ2VXaWR0aAAyMTHrqE6dAAAAEnRFWHRleGlmOkV4aWZPZmZzZXQANjTZeQZNAAAAGnRFWHRleGlmOlNvZnR3YXJlAFBob3RvcyAyLjcuMIcagsYAAAAASUVORK5CYII=)]([https://colab.research.google.com/github/mrbvrz/dicoding-machine-learning-developer/blob/master/belajar-machine-learning-untuk-pemula/01/rockpaperscissors.ipynb](https://colab.research.google.com/drive/18KMLKdL1DuW1dcJgFWhne-Z0I9u1klix?usp=sharing))

Thank you for exploring this NLP project! :pray:

Your feedback is valuable, and contributions are welcome to enhance its quality and functionality.
