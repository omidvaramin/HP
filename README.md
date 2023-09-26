# Headline Popularity (HP) Dataset
This dataset was created as part of our work in "Learning to Generate Popular Headlines". You can download the article from the following link:
https://ieeexplore.ieee.org/document/10154027

We use the tweets ID from Clickbait challenge 2017 (https://zenodo.org/record/5530410) dataset to crawl the information regarding the tweets using Twitter API. 

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

The trained models for headline generaion on Newsroom dataset are as follows:<br />
| Model | Link |
| :---         | :---      |
|Fine tuned of Prophet-Net | [Hprophetnet-large](https://huggingface.co/omidvaramin/Hprophetnet-large)  |
|Fine tuned of Bart | [HBART](https://huggingface.co/omidvaramin/HBART)  |
|Fine tuned of t5 | [Ht5-small](https://huggingface.co/omidvaramin/Ht5-small)  |

If you find the dataset useful, please cite our article:

@ARTICLE{10154027,<br />
author={Omidvar, Amin and An, Aijun},<br />
journal={IEEE Access}, <br />
title={Learning to Generate Popular Headlines}, <br />
year={2023},<br />
volume={11},<br />
number={},<br />
pages={60904-60914},<br />
doi={10.1109/ACCESS.2023.3286853}}



