# UrduFNDataset: A Comprehensive Dataset for Enhancing Fake News Detection in Urdu Using Transformer Models

## Introduction

UrduFNDataset is a meticulously curated dataset aimed at improving fake news detection in Urdu using transformer models. This dataset was collected using a combination of automated data crawling, deep learning techniques, and rigorous human verification. It covers four key news categories: business, sports, crimes, and entertainment, making it a valuable resource for researchers and developers working on natural language processing (NLP) and fake news detection in Urdu.

## Dataset Collection

The UrduFNDataset was collected through a combination of automated data crawling, deep learning models, and manual verification. Using Python's Selenium and BeautifulSoup libraries, we scraped news articles from [*dunya.com.pk*](https://dunya.com.pk/index.php/archive), focusing on the four categories: business, sports, crimes, and entertainment. All scraped articles were filtered to ensure uniqueness and reliability, with redundant content removed through manual checks. To create fake news samples, we leveraged pre-trained transformer models to generate content against real news articles. Each generated article was manually refined and verified to ensure accuracy, resulting in a comprehensive and reliable dataset for further analysis.

## Dataset Structure

The UrduFNDataset is organized into four categories: business, sports, crimes, and entertainment. It comprises a total of 2,880 news articles, with 2,304 designated for training and 576 for testing. The dataset is evenly split between real and fake news, containing 1,600 real articles and 1,280 fake articles. The training set includes 1,280 real and 1,024 fake articles, while the test set is composed of 320 real and 256 fake articles. The distribution of news articles across categories is balanced, ensuring a robust dataset for model training and evaluation.

### Dataset Statistics Tables

Here are the tables that describe the distribution of real and fake news articles:

#### Table 1: Distribution of Real and Fake News

| Dataset | Real | Fake | Total |
|---------|------|------|-------|
| Train   | 1280 | 1024 | 2304  |
| Test    | 320  | 256  | 576   |

#### Table 2: Training Data Distribution by Category

| Category     | Business | Sports | Crimes | Entertainment | Total |
|--------------|----------|--------|--------|---------------|-------|
| Real         | 320      | 320    | 320    | 320           | 1280  |
| Fake         | 256      | 256    | 256    | 256           | 1024  |

#### Table 3: Test Data Distribution by Category

| Category     | Business | Sports | Crimes | Entertainment | Total |
|--------------|----------|--------|--------|---------------|-------|
| Real         | 80       | 80     | 80     | 80            | 320   |
| Fake         | 64       | 64     | 64     | 64            | 256   |

---
