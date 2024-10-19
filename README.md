# Presentation SelfClean

I collected 100 images from the HSLU campus in horw and 91 images 
from the Rotkreuz campus. The goal of the selfClean package
([Digital Dermatology - SelfClean Repository](https://github.com/Digital-Dermatology/SelfClean/tree/main))
 will be to detect data quality issues such as near duplicates, outliers and mislabeled iamges.  

## Mislabeled Image
I intentionally moved the image "Horw_2439.JPG," which was taken in Horw, into the folder for Rotkreuz.
The goal of the SelfClean is the identify this image as mislabeled.

<p float="left">
  <img src="./Dataset/Rotkreuz/Horw_2439.JPG" width="200" />
</p>

## Outliers
Outliers are defined as images that are not taken on the campus of HSLU. These are the outliers in the Rotkreuz subfolder: 
- Rotkreuz_2552.JPG
- Rotkreuz_9975.JPG
<p float="left">
  <img src="./Dataset/Rotkreuz/Rotkreuz_2552.JPG" width="200" />
 <img src="./Dataset/Rotkreuz/Rotkreuz_9975.jpg" width="200" />
</p>

The subfolder "Horw" contains the following two outliers: 
- Horw_7789.JPG
- Horw_0517.JPG
<p float="left">
  <img src="./Dataset/Horw/Horw_7789.jpg" width="200" />
 <img src="./Dataset/Horw/Horw_0517.jpg" width="200" />
</p>

## Near Duplicates 
During the dataset collection, I took multiple images of the same object but different angle. The goal of the SelfClean package is to identify these images. 
These are my expected near duplicates: <br>
**Expected Near Duplicates 1**
- Horw_2385.JPG
- Horw_2386.JPG

<p float="left">
  <img src="./Dataset/Horw/Horw_2385.JPG" width="200" />
  <img src="./Dataset/Horw/Horw_2386.JPG" width="200" /> 
</p>


**Expected Near Duplicates 2**
- Horw_2419.JPG
- Horw_2422.JPG

<p float="left">
  <img src="./Dataset/Horw/Horw_2419.JPG" width="200" />
  <img src="./Dataset/Horw/Horw_2422.JPG" width="200" /> 
</p>

**Expected Near Duplicates 3**
- Horw_2424.JPG
- Horw_2425.JPG

<p float="left">
  <img src="./Dataset/Horw/Horw_2424.JPG" width="200" />
  <img src="./Dataset/Horw/Horw_2425.JPG" width="200" /> 
</p>

**Expected Near Duplicates 4**
- Rotkreuz_2476.JPG
- Rotkreuz_2477.JPG

<p float="left">
  <img src="./Dataset/Rotkreuz/Rotkreuz_2476.JPG" width="200" />
  <img src="./Dataset/Rotkreuz/Rotkreuz_2477.JPG" width="200" /> 
</p>

