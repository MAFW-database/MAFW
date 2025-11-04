

# MAFW

## Details

<b>MAFW</b> is a large-scale, multi-modal, compound affective database for dynamic facial expression recognition in the wild. Clips in this database come from China, Japan, Korea, Europe, America and India, and cover various themes, e.g., variety, family, science fiction, suspense, love, comedy, and interviews, encompassing a wide range of human emotions. Each clip has been independently labeled 11 times by 11 well-trained annotators. MAFW database has enormous diversities, large quantities, and rich annotations, including:

- <b>10,045</b> number of video clips from movies, TV dramas, and short videos,
- a <b>11-dimensional</b>  expression distribution vector for each video clip,
- <b>three kinds of annotations</b>: (1) single expression label; (2) multiple expression label; (3) bilingual emotional descriptive text,
-  <b>two subsets</b>: single-expression set, including <b>11</b> classes of <b>single</b>  emotions; multiple-expression set, including  <b>32</b> classes of  <b>multiple </b>emotions,
-  <b>three automatic annotations</b>: the frame-level 68 facial landmarks, bounding boxes of face regions, and gender,
- <b>four benchmarks</b> : uni-modal single expression classification, multi-modal single expression classification, uni-modal compound expression classification, and multi-modal compound expression classification.


## Sample Video-audio Clips


### 1. Examples of the single expressions in MAFW

<table id="tfhover" class="tftable" border="1">
<tr><td width="30%"><image src="samples-gif/anger_07317_4s.gif" /></td><td width="15%"><b>Anger</b></td><td>English: A girl with tears in her eyes shouts at the person opposite her. The deep frown,a downward pull on the lip corners,the higher inner corners of eyebrows and the lower outer corners of eyebrows.<br />中文：一个女生眼含着泪水大声训斥着对面的人。眉头紧蹙，嘴角下拉，眉毛内高外低。</td></tr>
<tr><td><image src="samples-gif/disgust_07734.gif" /></td><td><b>Disgust</b></td><td>English: A woman looks nervously at her feet. The frown,the closed eyes and  the  open mouth.<br />中文：一个女人紧张的看着脚下的东西。皱眉，眼睛微闭，嘴巴张开。</td></tr>
<tr><td><image src="samples-gif/fear_09246.gif" /></td><td><b>Fear</b></td><td>English: A girl gasps in the dark. The wide eyes and the open mouth.<br />中文：一个女孩在昏暗的环境中急促的喘息。瞪眼，嘴巴张大。</td></tr>
<tr><td><image src="samples-gif/happy_01440.gif" /></td><td><b>Happiness</b></td><td>English: A woman communicates with a man, talking about dinner. The slightly closed eyes, the open mouth and the raised lip corners.<br />中文：一个女人与男人交流，谈论着晚餐。眼睛微闭，嘴巴张开，嘴角上扬。</td></tr>
<tr><td><image src="samples-gif/sad_00467.gif" /></td><td><b>Sadness</b></td><td>English: A girl stands on the beach, tilting her head back and crying. The deep frown and the wide open mouth.<br />中文：一个女孩站在海边，仰着头哭泣。眉头紧蹙，嘴巴张大。</td></tr>
<tr><td><image src="samples-gif/surprise_15152.gif" /></td><td><b>Surprise</b></td><td>English: The woman sits with her eyes slowly widening, then suddenly shivers back and asks in a confused voice. The wide eyes.<br />中文：女人坐着眼睛慢慢睁大，然后突然向后颤动了一下，慌乱地询问道。瞪眼。</td></tr>
<tr><td><image src="samples-gif/contempt_08668.gif" /></td><td><b>Contempt</b></td><td>English: A woman gives a dismissive laugh. A curl of the lips.<br />中文：一个女人不屑地笑了一声。撇嘴。</td></tr>
<tr><td><image src="samples-gif/anxiety_07499.gif" /></td><td><b>Anxiety</b></td><td>English: A woman can't get through to the phone and grumbles impatiently. The  frown and the compressed lips.<br />中文：一个女人打不通电话，不耐烦地埋怨了一声。皱眉，抿嘴。</td></tr>
<tr><td><image src="samples-gif/helplessness_08581.gif" /></td><td><b>Helplessness</b></td><td>English: A maid stands thoughtfully behind her mistress. The wide eyes and the compressed lips.<br />中文：一个侍女若有所思地站在女主人身后。瞪眼，抿嘴。</td></tr>
<tr><td><image src="samples-gif/disappointment_09683.gif" /></td><td><b>Disappointment</b></td><td>English: A man lowers his head and takes a deep breath. The open mouth and the trembling lips.<br />中文：一个男人低下头，深呼吸。嘴巴半张，嘴唇颤抖。</td></tr>
<tr><td><image src="samples-gif/neutral_00120_3s.gif" /></td><td><b>Neutral</b></td><td>-</td></tr>
</table>

### 2. Examples of the multiple expressions in MAFW

<table id="tfhover" class="tftable" border="1">
<tr><td width="30%"><image src="samples-gif/anger-disgust_08827.gif" /></td><td width="15%"><b>Anger<br/>Disgust</b></td><td>English: A man glances his head to the side at the words of the man in front of him. The frown and a downward pull on the lip corners.<br />中文：一个男人听到面前的男人的话语后将头瞥向一边。皱眉，嘴角下拉。</td></tr>
<tr><td><image src="samples-gif/fear_sad_07213.gif" /></td><td><b>Fear<br/>Sadness</b></td><td>English: A woman squats on the ground and talks to a man tearfully. The marked frown and a downward pull on the lip corners.<br />中文：一个女人蹲坐在地上满含泪水的在和男人说话。皱眉，嘴角下拉。</td></tr>
<tr><td><image src="samples-gif/fear-sad-anxiety_09878.gif" /></td><td><b>Fear<br/>Sadness<br/>Anxiety</b></td><td>English: A woman begs someone. The marked frown, the wide eyes and the slightly open mouth.<br />中文：一个女人哀求着。皱眉，瞪眼，嘴巴微张。</td></tr>
<tr><td><image src="samples-gif/anger-disgust-contempt_15120.gif" /></td><td><b>Anger<br/>Disgust<br/>Contempt</b></td><td>English: A woman makes a condescending sarcasm at the other person. The raised chin, the raised eyebrows, the closed eyes and the frown.<br />中文：一个女人居高临下地挖苦对方。下巴上扬，挑眉，闭眼，皱眉。</td></tr>
</table>


## Terms & Conditions

- MAFW database is available for  <b>non-commercial research purposes </b> only.
- You agree  <b>not to </b> reproduce, duplicate, copy, sell, trade, resell or exploit for commercial purposes, any portion of the clips, and any derived data.
- You agree  <b>not to </b> further copy, publish, or distribute any portion of the MAFW database. Except for internal use at a single site within the same organization, it is allowed to make copies of the dataset.



## How to get the MAFW Dataset

This database is publicly available and free for **professors and research scientists affiliated to a university**.  For students interested in accessing the dataset, please note that the application requires formal endorsement by a faculty member from your institution.

Permission to use (but not reproduce or distribute) the MAFW database is granted only if the following steps are properly followed:
1.  Download the [MAFW-academics -final.pdf](/academics/mafw-academics-final.pdf) document, which serves as the End-User License Agreement (EULA).
2.  Carefully review the terms and conditions to confirm acceptance.  The required information at the end of the document must be completed and signed—**for student applicants, this signature must be from a professor at their affiliated university** to validate the request.
3.  Send the fully completed and signed document to: 1202411179@cug.edu.cn.
4.  After review and approval, you will receive download links via email, including two options: **Baidu Netdisk** and **Google Drive**.

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
Please cite our paper if you find our work useful for your research:
- Yuanyuan Liu, Wei Dai, Chuanxu Feng, Wenbin Wang, Guanghao Yin, Jiabei Zeng, and Shiguang Shan. 2022. MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild. In Proceedings of the 30th ACM International Conference on Multimedia (MM ’22), October 10–14, 2022, Lisboa, Portugal. ACM, New York, NY, USA, 9 pages. https://doi.org/10.1145/3503161.3548190

```
@inbook{liu_mafw_2022,
	author = {Liu, Yuanyuan and Dai, Wei and Feng, Chuanxu and Wang, Wenbin and Yin, Guanghao and Zeng, Jiabei and Shan, Shiguang},
	title = {MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild},
	year = {2022}
	isbn = {978-1-4503-9203-7},
	publisher = {ACM},
	address = {New York, NY, USA},
	url = {https://doi.org/10.1145/3503161.3548190},
	booktitle = {Proceedings of the 30th ACM International Conference on Multimedia (MM’22)},
	numpages = {9}
}
```

## Content Preview

- Data

<image src="samples-gif/data.png" height="130" />

- Labels

<image src="samples-gif/labels.png" height="130" />

- Labels (auto)

<image src="samples-gif/auto_labels.png" height="130" />

- Train & Test Set

<image src="samples-gif/train&test.png" height="130" />

For more details of the dataset, please refer to the paper: [MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild](/academics/MAFW_final.pdf).

For more details of emotional descriptive texts, please refer to [supplementary materials](/academics/MAFW_supp.pdf) for MAFW.


## Frequently Asked Questions (FAQ)

### 1. What is the difference between the Baidu Netdisk and Google Drive download links?
After your application is approved, you will receive two download options:
- **Baidu Netdisk**: Contains the complete dataset, including frame data.
- **Google Drive**: Does not include frame data (only video clips and label files).

### 2. What should I do if I can't access Baidu Netdisk but need frame data?
If you require frame data but cannot access Baidu Netdisk, you can extract and process frames from the video clips obtained via Google Drive using the following steps (consistent with the preprocessing pipeline in our paper):
1. **Extract frame pictures** from video clips using tools like OpenCV.
2. **Face detection and landmark extraction**: Use face recognition tools (e.g., [face-alignment-master](https://github.com/1adrianb/face-alignment) referenced in our paper, or other convenient face detection libraries) to identify face regions and 68 facial landmarks.
3. **Face alignment and resizing**: Perform affine transformation and matrix rotation (via OpenCV or similar libraries) to align faces, then resize the aligned face regions to **224×224 pixels** (consistent with the dataset's standard format).

You may use any familiar face detection, landmark extraction, or alignment tool that suits your workflow— the key is to ensure the final output is 224×224 aligned face frames for consistency with the dataset's benchmark settings.

### 3. How to handle split compressed files (e.g., clips and frames)?
Due to the large size of the `clips` and `frames` directories, they are split into multiple compressed files:
- Clips: `clips.7z.001`, `clips.7z.002`, ... (sequential numbering)
- Frames: `frames.7z.001`, `frames.7z.002`, ..., `frames.7z.010` (up to 10 parts)

**Extraction instructions:**
- **Windows**: Use 7-Zip or WinRAR. Right-click the first file (e.g., `clips.7z.001` or `frames.7z.001`) and select "Extract here" – the software will automatically merge all parts into a single folder.
- **Linux/macOS**: Use the `7z` command in the terminal. Run `7z x clips.7z.001` (or `frames.7z.001`) – the tool will detect and process all related parts sequentially.

**Critical notes:**
1. Ensure all split files are in the **same folder** (do not separate them into subdirectories).
2. Do **not rename** any split files (e.g., avoid changing `clips.7z.001` to `clips_part1.7z`), as this will break the extraction sequence.
3. Verify that all files are fully downloaded (no corruption or missing parts) – incomplete downloads will cause extraction failures.
4. The final extracted folder will be named `clips` or `frames` (no need to manually merge folders).

##  Code
The source code of our proposed T-ESFL model can be downloaded in [https://github.com/MAFW-database/MAFW](https://github.com/MAFW-database/MAFW).

## Contact 

Please contact us for any questions about MAFW.
<table id="tfhover" class="tftable" border="1">
<tr><td width="20%">Yuanyuan Liu</td><td width="65%">Associate Professor, China University of Geosciences</td><td width="15%"><a href="mailto:liuyy@cug.edu.cn">liuyy@cug.edu.cn</a></td></tr>
<tr><td>Shuyang Liu</td><td>Master, China University of Geosciences</td><td><a href="mailto:20171003670@cug.edu.cn">20171003670@cug.edu.cn</a></td></tr>
<tr><td>Ying Qian</td><td>Master, China University of Geosciences</td><td><a href="mailto:1202411179@cug.edu.cn">1202411179@cug.edu.cn</a></td></tr>
</table>

For more information, welcome to visit our team's homepage: [https://cvlab-liuyuanyuan.github.io/](https://cvlab-liuyuanyuan.github.io/)


