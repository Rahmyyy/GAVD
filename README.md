# GAVD
Gait Abnormality in Video Dataset (GAVD) is the largest collection of online links to gait videos with clinical annotations. The dataset is designed for Clinical Gait Analysis using computer vision however has many applicaitons such as gait recognition and abnormality action detection. For further details regarding dataset please see [LINK TO PAPER IN ARXIV]

<img src="figures/GAVD_examples.png" alt="GAVD example frames" width="900"/>

## Dataset Features

<img src="figures/gavd_features_summary.png" alt="GAVD Dataset Features" width="600"/>

<img src="figures/Example Gait Category Numbers2.png" alt="Gait Subclasses" width="600"/>

<img src="figures/gavd_gait_classes.png" alt="GAVD Subclass Classification" width="600"/>

<img src="figures/person-centric.png" alt="Camera View Annotations" width="600"/>

## Data Structure
Data is provided as pkl files part 1 to 5 or csv files part 1 to 5.

|*Data Column*|*Description*|
|:-----------------:|:--------:|
| seq |   sequnce ID unique to a section of gait in single direction  |

seq - sequnce ID unique to a section of gait in single direction
frame_num - corresponding frame number of video
cam_view - Annotated person-centric view
gait_event - clinically annotated gait event (NOTE: this is limited in this current dataset)
dataset - general classificaiton of normal and abnomral gait
gait_pat - clinically annotated classification of gait from observation by clinican
bbox - bounding box values tracking indiviuals gait
vid_info - video related metadata
id - video youtube id
url - url to access video

<img src="figures/GAVD_data_sample.png" alt="Example GAVD Annotation Data Structure" width="900"/>
