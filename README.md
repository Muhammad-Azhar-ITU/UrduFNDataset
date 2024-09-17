# UrduFNDataset: A Comprehensive Dataset for Enhancing Fake News Detection in Urdu Using Transformer Models

## Introduction

UrduFNDataset is a meticulously curated dataset aimed at improving fake news detection in Urdu using transformer models. The UrduFNDataset was collected through a combination of automated data crawling, deep learning models, and manual verification. It covers four key news categories: business, sports, crimes, entertainment, and politics, making it a valuable resource for researchers and developers working on natural language processing (NLP) and fake news detection in Urdu. Real news are scraped from [*dunya.com.pk*](https://dunya.com.pk/index.php/archive). All scraped articles were filtered to ensure uniqueness and reliability, with redundant content removed through manual checks. To create fake news samples, we leveraged pre-trained transformer models to generate content against real news articles. Each generated article was manually refined and verified to ensure accuracy, resulting in a comprehensive and reliable dataset for further analysis.

## Dataset Structure

The UrduFNDataset is organized into five categories: business, sports, crimes, entertainment, and politics. It comprises a total of 3,600 news articles, with 2,880 designated for training and 720 for testing. The dataset is evenly split between real and fake news, containing 2,000 real articles and 1,600 fake articles. The training set includes 1,600 real and 1,280 fake articles, while the test set is composed of 400 real and 320 fake articles. The distribution of news articles across categories is balanced, ensuring a robust dataset for model training and evaluation.

### Dataset Statistics Tables

Here are the tables that describe the distribution of real and fake news articles:

#### Table 1: Distribution of Real and Fake News

| Dataset | Real | Fake | Total |
|---------|------|------|-------|
| Train   | 1600 | 1280 | 2880  |
| Test    | 400  | 320  | 720   |

#### Table 2: Training Data Distribution by Category

| Category     | Business | Sports | Crimes | Entertainment | Politics | Total |
|--------------|----------|--------|--------|---------------|----------|-------|
| Real         | 320      | 320    | 320    | 320           | 320      | 1600  |
| Fake         | 256      | 256    | 256    | 256           | 256      | 1280  |


#### Table 3: Test Data Distribution by Category

| Category     | Business | Sports | Crimes | Entertainment | Politics | Total |
|--------------|----------|--------|--------|---------------|----------|-------|
| Real         | 80       | 80     | 80     | 80            | 80       | 400   |
| Fake         | 64       | 64     | 64     | 64            | 64       | 320   |

---
