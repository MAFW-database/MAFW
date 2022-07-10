

## Details

<b>MAFW</b> is a large-scale, multi-modal, compound affective database for dynamic facial expression recognition in the wild. Clips in this database come from China, Japan, Korea, Europe, America and India, and cover various themes, e.g., variety, family, science fiction, suspense, love, comedy, and interviews, encompassing a wide range of human emotions. Each clip has been independently labeled 11 times by 11 well-trained annotators. MAFW database has enormous diversities, large quantities, and rich annotations, including:

- <b>10,045</b> number of video clips from movies, TV dramas, and short videos
- a <b>11-dimensional</b>  expression distribution vector for each video clip
- three kinds of annotations: (1) single expression label; (2) multiple expression label; (3) bilingual emotional descriptive text
- <b>two subsets</b>: single-expression set, including 11 classes of single emotions; multiple-expression set, including 32 classes of multiple emotions
- automatic annotaions including  <b>68 landmark locations</b>, bounding box, and gender attributes per video
- baseline classifier outputs based on uni-modal single expression classification, uni-modal  compound expression classification, multi-modal single expression classification, and multi-modal compound expression classification.


## Samples Videos


### 1.1 Examples of the single expressions in MAFW

![image](imgs/image03.png)

### 1.2 Examples of the multiple expressions in MAFW
![image](imgs/image04.png)


## Terms & Conditions

- MAFW database is available for  <b>non-commercial research purposes </b> only.
- You agree  <b>not to </b> reproduce, duplicate, copy, sell, trade, resell or exploit for commercial purposes, any portion of the clips, and any derived data.
- You agree  <b>not to </b> further copy, publish, or distribute any portion of the MAFW database. Except for internal use at a single site within the same organization, it is allowed to make copies of the dataset.



###  How to get the MAFW Dataset

This database is publicly available. It is free for professors and researcher scientists affiliated to a University.

Permission to use but not reproduce or distribute the MAFW database is granted to all researchers given that the following steps are properly followed:
1. Download the [mafw-academics -final.pdf](/academics/mafw-academics-final.pdf) document.
2. Read the terms and conditions carefully to make sure they are acceptable, and fill in the relevant information at the end of the document.
3. Send the completed document to email (ygh2@cug.edu.cn).

### Content preview


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

03747.mp4  anger  <br>一个男人对着面前的激动地说话。眉头紧蹙，微微皱鼻。 <br> A man speaks excitedly to the man in front of him. The deep frown and the slightly wrinkled nose.

An example in the multi_label.txt is:

20045.mp4	anger_disgust_anxiety	<br>一个女人在门口苦口婆心地劝说朋友。皱眉，眉毛内低外高，鼻子微皱，噘嘴，嘴角下拉。	<br>A woman in a doorway painstakingly persuads her friend. The frown, the lower inner corners of eyebrows, the higher outer corners of eyebrows, the slightly wrinkled nose, a pout, and a downward pull on the lip corners.


## Citation

- [MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild]()

Please cite our paper if you find our work useful for your research:

```
@inproceedings{xxxxxx,

  title={MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild},

  author={xxxxxx},

  booktitle={xxxxxx},

  pages={xx--xx},

  year={xxxx},

}
```
##  Code

MAFW [Code Link]:(https://github.com/MAFW-datset/mafw).

## Contact 

If you have any questions about the dataset, please contact us by email.
| Contacts | Email |
| ------ | ------ |
| Yuanyuan Liu (Associate Professor, China University of Geosciences)| liuyy@cug.edu.cn|
| Guanghao Yin (Student, China University of Geosciences) | ygh2@cug.edu.cn |


Also, visit our team research home page at https://cvlab-liuyuanyuan.github.io/


