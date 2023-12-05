# Headline Popularity 
## Training 

| Code | Description |
| :---         | :---      |
| [Tuning_headline_Popularity_Model.ipynb](https://github.com/omidvaramin/HP/blob/main/Tuning_headline_Popularity_Model.ipynb)| This code is used to train a transformer encoder model for headline popularity prediciton task. |
| [Evaluator.ipynb](https://github.com/omidvaramin/HP/blob/main/Evaluator.ipynb)| This code is used to generate 10 variations of headlines for each news articles, select the most popular ones, and then calculate the evaluation metrics (i.e., ROUGE, BLEU, and METEOR) |


## Headline Popularity Dataset
This dataset was created as part of our work in "Learning to Generate Popular Headlines". You can download the article from [this link](https://ieeexplore.ieee.org/document/10154027)

We use the tweets ID from Clickbait challenge 2017 dataset ( [link](https://zenodo.org/record/5530410)) to crawl the information regarding the tweets using Twitter API. 

The post_text and target_paragraphs fields were derived from the clickbait challenge dataset but the rest of the fields were obtained from Twitter. 
The description of the fields is as following:<br />
| Field | Description |
| :---         | :---      |
| ID | a unique Tweet identification number     |
| post_text | a posted headline on Twitter (i.e., title)     | 
| target_paragraphs   |  a news article (i.e., body)     |
| favorite_count     | a number of likes       | 
| retweet_count     | a number of retweets       | 
| created_at     | a timestamp of a Tweet       | 
| users_followers_count     | a number of followers of a news media's Twitter account      | 
| user_name     | a news media's user name (i.e., news media)      | 
| user_description     | further information regarding news media       | 
| user_url     | URL of news media      | 

## Models
A trained headline popularity prediction model on HP dataset:<br />
| Model | Link |
| :---         | :---      |
|Headline Popularity Prediction | [HeadlinePopularity](https://huggingface.co/omidvaramin/HeadlinePopularity)  |

The trained models for headline generaion on Newsroom dataset are as follows:<br />
| Model | Link |
| :---         | :---      |
|Fine-tuned of Prophet-Net | [Hprophetnet-large](https://huggingface.co/omidvaramin/Hprophetnet-large)  |
|Fine-tuned of BART | [HBART](https://huggingface.co/omidvaramin/HBART)  |
|Fine-tuned of T5 | [Ht5-small](https://huggingface.co/omidvaramin/Ht5-small)  |

For more information, please read the following article:

@ARTICLE{10154027,<br />
author={Omidvar, Amin and An, Aijun},<br />
journal={IEEE Access}, <br />
title={Learning to Generate Popular Headlines}, <br />
year={2023},<br />
volume={11},<br />
number={},<br />
pages={60904-60914},<br />
doi={10.1109/ACCESS.2023.3286853}}



