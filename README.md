# Project Title
Psychology-Informed Natural Language Understanding: Integrating Personality and Emotion-Aware Features for Comprehensive Sentiment Analysis and Depression Detection 


### Prerequisites

Create environment

```
conda env create -f environment.yml
```

# Dataset
Type	Model Task	Dataset	Description & Splitting
Psycho	Personality Recognition	MBTI-PersonalityCafe (Mitchell, 2017)
    The dataset was gathered in Reddit and comprises documents labelled with MBTI (Myers-Briggs Type Indicator) types, which include 16 specific types or four binary labels.
https://huggingface.co/datasets/jingjietan/kaggle-mbti (Tan, 2024b)

        MBTI-Reddit  (Robbert Deimann et al., 2017)
 The dataset, available upon request, was gathered from Reddit and consists of documents labeled with MBTI types, encompassing 16 distinct personality types or four binary category labels.
    Emotion Recognition	GoEmotions
(Demszky et al., 2020)
Gathered from Reddit, this dataset includes text along with categorization into 27 distinct emotions and a Neutral category.
https://huggingface.co/datasets/willcb/go-emotion (Demszky et al., 2020)

        CombinedDataset (Hartmann, 2022)
Merged from six open datasets, this combined dataset was refined by removing certain classes, resulting in a final set of seven classes.
https://huggingface.co/j-hartmann/emotion-english-distilroberta-base (Hartmann, 2022)

NLU	Sentiment Analysis	Polarity (v2.0)
(Pang & Lee, 2004)
Comprising 1,000 movie review comments, this dataset is labelled with either positive or negative sentiments.
https://huggingface.co/datasets/jingjietan/polarity-sentiment (Tan, 2024c)

        IMDb
(Maas et al., 2011a)
Composed of 50,000 comments on movie reviews, expressed in positive or negative.
https://huggingface.co/datasets/jingjietan/imdb-sentiment (Tan, 2024a)

    Depression Detection	Twitter (now known as X)
(Shinde, 2022)
Derived from Twitter posts, this dataset consists of 20,000 entries labelled as either indicating depression or not.
https://huggingface.co/datasets/jingjietan/twitter-depression (Tan, 2024e)

        SDCNL
(Haque et al., 2021)
Gathered from 1,895 Reddit posts, this dataset is labelled based on the presence of suicide intent.
https://huggingface.co/datasets/jingjietan/sdcnl-suicide (Tan, 2024d)


