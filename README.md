# Headline Popularity (HP) Dataset
This dataset was created as part of our work in "Learning to Generate Popular Headlines". You can download the article from the following link:
https://ieeexplore.ieee.org/document/10154027

We use the tweets ID from Clickbait challenge 2017 (https://zenodo.org/record/5530410) dataset to crawl the information regarding the tweets from Twitter. <br />
The post_text and target_paragraphs fields were derived from the clickbait challenge dataset but the rest of the fields were obtained from Twitter. 
The description of the fields is as following:
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



If you find the dataset useful, please cite our article:

@ARTICLE{10154027,
author={Omidvar, Amin and An, Aijun},
  
  journal={IEEE Access}, 
  
  title={Learning to Generate Popular Headlines}, 
  
  year={2023},
  
  volume={},
  
  number={},
  
  pages={1-1},
  
  doi={10.1109/ACCESS.2023.3286853}}


