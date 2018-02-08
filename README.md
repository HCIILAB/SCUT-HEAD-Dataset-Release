# News
**2018-1-16** SCUT-HEAD v1.0 is released with images and head bounding box annotations.
# Description
SCUT-HEAD is a large-scale head detection dataset, including 4405 images labeld with 111251 heads. The dataset consists of two parts. PartA includes 2000 images sampled from monitor videos of classrooms in an university with 67321 heads annotated. PartB includes 2405 images crawled from Internet with 43930 heads annotated. We have labelled every visable heads with xmin, ymin, xmax and ymax coordinates and ensured that annotations cover the entire head including the blocked parts but without extra background. Both PartA and PartB are divided into training and testing parts. Our dataset follows the standard of Pascal VOC. 

## PartA 
PartA includes 2000 images sampled from monitor videos of classrooms in an university with 67321 heads annotated. 1500 images of PartA are for training and 500 for testing.
Because classrooms in an university usually looks similar and the poses of people vary less, we carefully choose representative images to gain variance and reduce similarity. 
Representative image and annotations and the histogram of people counts are shown below.

<div align="center">
	<a style="float:left; padding:10px">
		<img width="45%" height="250px" src="https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release/blob/master/Representative_image_of_PartA.jpg" >
	</a>
	<a style="float:right; padding:10px">
		<img width="45%" height="250px" src="https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release/blob/master/histogram_of_people_counts_PartA.jpg">
	</a>
</div>
<!-- ![image](https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release/blob/master/example%20of%20Part_A.jpg) -->


## PartB 
PartB includes 2405 images with 43940 heads annotated. 1905 images of PartB are for training and 500 for testing. The images are crawled from Internet (Baidu and Google), the urls of images are provided as followed.
Representative image and annotations and the histogram of people counts are shown below.

<div align="center">
	<a style="float:left; padding:10px">
		<img width="45%" height="250px" src="https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release/blob/master/Representative_image_of_PartB.jpg" >
	</a>
	<a style="float:right; padding:10px">
		<img width="45%" height="250px" src="https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release/blob/master/histogram_of_people_counts_PartB.jpg">
	</a>
</div>
<!-- ![image](https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release/blob/master/example%20of%20Part_B.jpg) -->

# Download
PartA of SCUT-HEAD 
[[Google Drive]](https://drive.google.com/open?id=1DWZHnmcOR8H9adXRRMV_DaOLCnBEcMLi)[[Baidu Drive]](https://pan.baidu.com/s/1c3oryVI)

PartB of SCUT-HEAD 
[[Google Drive]](https://drive.google.com/open?id=1G298UFgHElio4c5UdyvR9LsP7kJscOlJ)
[[Baidu Drive]](https://pan.baidu.com/s/1mjv2EgC)

# Related Datasets
[**HollywoodHead dataset**](http://www.di.ens.fr/willow/research/headdetection/)
HolleywoodHeads dataset is a head detection datset. HollywoodHeads dataset contains 369846 human heads annotated in 224740 video frames from 21 Hollywood movies.

[**Brainwash dataset**](https://exhibits.stanford.edu/data/catalog/sx925dc9385) 
Brainwash dataset is related for face detection. Brainwash dataset contains 11917 images with 91146 labeled people.

# Citation and Contact

Please consider to cite our paper Dezhi Peng, Zikai Sun, Zirong Chen, Zirui Cai, Lele Xie, Lianwen Jin, “Detecting Heads using Feature Refine Net and Cascaded Multi-scale Architecture” when you use our database. 

For any questions about this database please contact the authors by sending email to eelwjin@scut.edu.cn and eedzpeng@mail.scut.edu. 
