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
PartB includes 2405 images with 43940 heads annotated. 1905 images of PartB are for training and 500 for testing. The images are crawled from Internet. The urls of images are also provided in the dataset.
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
[[Google Drive]](https://drive.google.com/open?id=1yaOF9os5wPVNNG4GVzNyULLVe74vdrBE)
[[Baidu Drive]](https://pan.baidu.com/s/1EQtyLwDfEULsdSy-UZhzWQ)

PartB of SCUT-HEAD 
[[Google Drive]](https://drive.google.com/open?id=1LZ_KlTPStDEcqycfqUkDkqQ-aNMMC3cl)
[[Baidu Drive]](https://pan.baidu.com/s/1CASxJBkjKoW3_yO8OVKBvQ)

# Related Datasets
[**HollywoodHead dataset**](http://www.di.ens.fr/willow/research/headdetection/)
HolleywoodHeads dataset is a head detection datset. HollywoodHeads dataset contains 369846 human heads annotated in 224740 video frames from 21 Hollywood movies.

[**Brainwash dataset**](https://exhibits.stanford.edu/data/catalog/sx925dc9385) 
Brainwash dataset is related for face detection. Brainwash dataset contains 11917 images with 91146 labeled people.

# Citation and Contact

Please consider to cite our paper when you use our database:

```
@article{peng2018detecting,
  title={Detecting Heads using Feature Refine Net and Cascaded Multi-scale Architecture},
  author={Peng, Dezhi and Sun, Zikai and Chen, Zirong and Cai, Zirui and Xie, Lele and Jin, Lianwen},
  journal={arXiv preprint arXiv:1803.09256},
  year={2018}
}
```

For any questions about this database please contact the authors by sending email to eelwjin@scut.edu.cn and pengdezhi000@gmail.com.
