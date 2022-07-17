
# MAFW

## Details

<b>MAFW</b> is a large-scale, multi-modal, compound affective database for dynamic facial expression recognition in the wild. Clips in this database come from China, Japan, Korea, Europe, America and India, and cover various themes, e.g., variety, family, science fiction, suspense, love, comedy, and interviews, encompassing a wide range of human emotions. Each clip has been independently labeled 11 times by 11 well-trained annotators. MAFW database has enormous diversities, large quantities, and rich annotations, including:

- <b>10,045</b> number of video clips from movies, TV dramas, and short videos
- a <b>11-dimensional</b>  expression distribution vector for each video clip
- <b>three kinds of annotations</b><br/> &emsp;&emsp;(1) single expression label<br />    &emsp;&emsp;(2) multiple expression label<br />  &emsp;&emsp;(3) bilingual emotional descriptive text
-  <b>two subsets</b>: single-expression set, including <b>11</b> classes of <b>single</b>  emotions; multiple-expression set, including  <b>32</b> classes of  <b>multiple </b>emotions
-  <b>three automatic annotations</b>: the frame-level 68 facial landmarks, bounding boxes of face regions, and gender
- <b>four benchmarks</b> : uni-modal single expression classification, uni-modal  compound expression classification, multi-modal single expression classification, and multi-modal compound expression classification.


## Samples Videos


### 1 Examples of the single expressions in MAFW

<table id="tfhover" class="tftable" border="1">
<tr><td width="700px"><image src="samples-gif/anger_07317_4s.gif" /></td><td><b>Anger</b></td><td>中文：一个女生眼含着泪水大声训斥着对面的人。眉头紧蹙，嘴角下拉，眉毛内高外低。<br />English: A girl with tears in her eyes shouts at the person opposite her. The deep frown,a downward pull on the lip corners,the higher inner corners of eyebrows and the lower outer corners of eyebrows.</td></tr>
<tr><td><image src="samples-gif/disgust_07734.gif" /></td><td><b>Disgust</b></td><td>中文：一个女人紧张的看着脚下的东西。皱眉，眼睛微闭，嘴巴张开。<br />English: A woman looks nervously at her feet. The frown,the closed eyes and  the  open mouth.</td></tr>
<tr><td><image src="samples-gif/fear_09246.gif" /></td><td><b>Fear</b></td><td>中文：一个女孩在昏暗的环境中急促的喘息。瞪眼，嘴巴张大。<br />English: A girl gasps in the dark. The wide eyes and the open mouth.</td></tr>
<tr><td><image src="samples-gif/happy_01440.gif" /></td><td><b>Happiness</b></td><td>中文：一个女人与男人交流，谈论着晚餐。眼睛微闭，嘴巴张开，嘴角上扬。<br />English: A woman communicates with a man, talking about dinner. The slightly closed eyes, the open mouth and the raised lip corners.</td></tr>
<tr><td><image src="samples-gif/sad_00467.gif" /></td><td><b>Sadness</b></td><td>中文：一个女孩站在海边，仰着头哭泣。眉头紧蹙，嘴巴张大。<br />English: A girl stands on the beach, tilting her head back and crying. The deep frown and the wide open mouth.</td></tr>
<tr><td><image src="samples-gif/surprise_15152.gif" /></td><td><b>Surprise</b></td><td>中文：女人坐着眼睛慢慢睁大，然后突然向后颤动了一下，慌乱地询问道。瞪眼。<br />English: The woman sits with her eyes slowly widening, then suddenly shivers back and asks in a confused voice. The wide eyes.</td></tr>
<tr><td><image src="samples-gif/contempt_08668.gif" /></td><td><b>Contempt</b></td><td>中文：一个女人不屑地笑了一声。撇嘴。<br />English: A woman gives a dismissive laugh. A curl of the lips.</td></tr>
<tr><td><image src="samples-gif/anxiety_07499.gif" /></td><td><b>Anxiety</b></td><td>中文：一个女人打不通电话，不耐烦地埋怨了一声。皱眉，抿嘴。<br />English: A woman can't get through to the phone and grumbles impatiently. The  frown and the compressed lips.</td></tr>
<tr><td><image src="samples-gif/helplessness_08581.gif" /></td><td><b>Helplessness</b></td><td>中文：一个侍女若有所思地站在女主人身后。瞪眼，抿嘴。<br />English: A maid stands thoughtfully behind her mistress. The wide eyes and the compressed lips.</td></tr>
<tr><td><image src="samples-gif/disappointment_09683.gif" /></td><td><b>Disappointment</b></td><td>中文：一个男人低下头，深呼吸。嘴巴半张，嘴唇颤抖。<br />English: A man lowers his head and takes a deep breath. The open mouth and the trembling lips.</td></tr>
<tr><td><image src="samples-gif/neutral_00120_3s.gif" /></td><td><b>Neutral</b></td><td>-</td></tr>
</table>

### 2 Examples of the multiple expressions in MAFW

<table id="tfhover" class="tftable" border="1">
<tr><td width="700px"><image src="samples-gif/anger-disgust_08827.gif" /></td><td><b>Anger_Disgust</b></td><td>中文：一个男人听到面前的男人的话语后将头瞥向一边。皱眉，嘴角下拉。<br />English: A man glances his head to the side at the words of the man in front of him. The frown and a downward pull on the lip corners.</td></tr>
<tr><td><image src="samples-gif/fear_sad_07213.gif" /></td><td><b>Fear_Sadness</b></td><td>中文：一个女人蹲坐在地上满含泪水的在和男人说话。皱眉，嘴角下拉。<br />English: A woman squats on the ground and talks to a man tearfully. The marked frown and a downward pull on the lip corners.</td></tr>
<tr><td><image src="samples-gif/fear-sad-anxiety_09878.gif" /></td><td><b>Fear_Sadness_Anxiety</b></td><td>中文：一个女人哀求着。皱眉，瞪眼，嘴巴微张。<br />English: A woman begs someone. The marked frown, the wide eyes and the slightly open mouth.</td></tr>
<tr><td><image src="samples-gif/anger-disgust-contempt_15120.gif" /></td><td><b>Anger_Disgust_Contempt</b></td><td>中文：一个女人居高临下地挖苦对方。下巴上扬，挑眉，闭眼，皱眉。<br />English: A woman makes a condescending sarcasm at the other person. The raised chin, the raised eyebrows, the closed eyes and the frown.</td></tr>
</table>


## Terms & Conditions

- MAFW database is available for  <b>non-commercial research purposes </b> only.
- You agree  <b>not to </b> reproduce, duplicate, copy, sell, trade, resell or exploit for commercial purposes, any portion of the clips, and any derived data.
- You agree  <b>not to </b> further copy, publish, or distribute any portion of the MAFW database. Except for internal use at a single site within the same organization, it is allowed to make copies of the dataset.



##  How to get the MAFW Dataset

This database is publicly available. It is free for professors and researcher scientists affiliated to a University.

Permission to use but not reproduce or distribute the MAFW database is granted to all researchers given that the following steps are properly followed:
1. Download the [MAFW-academics -final.pdf](/academics/mafw-academics-final.pdf) document.
2. Read the terms and conditions carefully to make sure they are acceptable, and fill in the relevant information at the end of the document.
3. Send the completed document to email (ygh2@cug.edu.cn).

<!--
## Content Preview
Below is a preview of the contents of our dataset.

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
An example in the single_label.txt is:<br>
03352.mp4  &emsp;&emsp;happiness	 &emsp; &emsp;&emsp;    一位男子手握一杯饮料，向别人介绍着这杯饮料。嘴角上扬。	 &emsp;A man holds a drink in his hand and introduces it to others. The raised lip corners.
<br>
<br>
An example in the multi_label.txt is:<br>
09932.mp4 &emsp;sadness_surprise &emsp;	一个女人听见一个噩耗，手机从耳边滑下。眉头紧蹙，瞪眼。	 &emsp;A woman hears a bad news and her mobile phone slips down her ear. The deep frown and the wide eyes.
<br>
<br>
For more details of the dataset, please refer to the paper ["MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild"](/academics/MAFW.pdf).
-->

## Citation

- [MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild](/academics/MAFW.pdf),in ACM Multimedia, 2022.

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
We have uploaded our code project on github.
<br>
You can download it from MAFW Code Link ([https://github.com/MAFW-database/MAFW](https://github.com/MAFW-database/MAFW)).

## Contact 

If you have any questions about the dataset, please contact us by email.
<br>
<br>
Yuanyuan Liu (Associate Professor, China University of Geosciences)([liuyy@cug.edu.cn]())
<br>
Guanghao Yin (Master, China University of Geosciences) ([ygh2@cug.edu.cn]())
<br>
Shaoze  Feng (Master, China University of Geosciences)([2807592236@cug.edu.cn]())
<br>
<br>
Also, visit our team research home page at [https://cvlab-liuyuanyuan.github.io/](https://cvlab-liuyuanyuan.github.io/)


