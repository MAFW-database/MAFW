

# MAFW


MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression  Recognition in the Wild. The data source of MAFW is richer, not only from movies and TV dramas, but also includes short videos from reality shows, talk shows, news, variety shows, etc, which is closer to the real-world emotion.

### Features

- 10,045 video-audio clips.
- Each clip is annotated with a compound emotional category and a couple of sentences that describe the subjects’ affective behaviors in the clip.
- multiple modalities in the wild.
- 11 single-emotion categories and 32 multi-emotion categories.


## 1. Samples of MAFW


### 1.1 Examples of the single expressions in MAFW

![image](https://github.com/yinhao2000/MAFW/blob/main/imgs/image03.png)

### 1.2 Examples of the multiple expressions in MAFW
![image](https://github.com/yinhao2000/MAFW/blob/main/imgs/image04.png)


## 2. Download the MAFW dataset

> **Note:** We have set out some of the terms and conditions in this section, as detailed in the [academics document](https://github.com/yinhao2000/MAFW/blob/main/academics/mafw-academics-final.pdf). Your E-mail MUST be set from a valid University account.

### 2.1 Some terms&conditions
- MAFW database is available for non-commercial research purposes only.
- You agree not to reproduce, duplicate, copy, sell, trade, resell or exploit for commercial purposes, any portion of the clips, and any derived data.
- You agree not to further copy, publish, or distribute any portion of the MAFW database. Except for internal use at a single site within the same organization, it is allowed to make copies of the dataset.



### 2.2 How to get the MAFW Dataset

> **Note:** This database is publicly available. It is free for professors and researcher scientists affiliated to a University.

Permission to use but not reproduce or distribute the MAFW database is granted to all researchers given that the following steps are properly followed:
1. Download the [mafw-academics -final.pdf](https://github.com/yinhao2000/MAFW/blob/main/academics/mafw-academics-final.pdf) document.
2. Read the terms and conditions carefully to make sure they are acceptable, and fill in the relevant information at the end of the document.
3. Send the completed document to email (wind_ygh@163.com).

### 2.3 Content preview


```
MAFW Dataset{
	clips: {
	       .....
	       00151.mp4,
	       00152.mp4,
	       00153.mp4,
	       .....
		}
	caption-label: {
		single_set : single_label.txt
		multi_Set : multi_label.txt		 
		}
	readme.txt
}
```
An example in the single_label.txt is:

03747.mp4  anger  一个男人对着面前的激动地说话。眉头紧蹙，微微皱鼻。  A man speaks excitedly to the man in front of him. The deep frown and the slightly wrinkled nose.

An example in the multi_label.txt is:

20045.mp4	anger_disgust_anxiety	一个女人在门口苦口婆心地劝说朋友。皱眉，眉毛内低外高，鼻子微皱，噘嘴，嘴角下拉。	A woman in a doorway painstakingly persuads her friend. The frown, the lower inner corners of eyebrows, the higher outer corners of eyebrows, the slightly wrinkled nose, a pout, and a downward pull on the lip corners.


## 3. Citation

- [MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild]()

Please cite our paper if you find our work useful for your research:

```
```

## 4.Contact 

If you have any questions about the dataset, please contact us by email.
| Contacts | Email |
| ------ | ------ |
|  | wind_ygh@163.com |


