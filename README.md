# GAVD  
Gait Abnormality in Video Dataset (GAVD) is the largest collection of online links to gait videos with clinical annotations. The dataset is designed for Clinical Gait Analysis using computer vision however has many applicaitons such as gait recognition and abnormality action detection. For further details regarding dataset please see the published paper  
[LINK TO IEEE ACCESS PAPER](https://ieeexplore.ieee.org/document/10921672).

## Access to Data Annotations  
Data annotations are publicly available in this repository  
[LINK TO DATA](https://github.com/Rahmyyy/GAVD/tree/main/data).  

They are available as CSV files or PKL file format. The full dataset annotations are provided as several files as we were unable to upload to GitHub as a single file due to upload size limits.

<img src="figures/GAVD_examples.png" alt="GAVD example frames" width="900"/>

## 📌 Dataset Access Policy – Important  
The **GAVD repository provides clinical annotations and metadata only**. It does **not** contain or distribute the original video files.

### ✅ What is included:
- Clinical labels (abnormality type, severity, gait notes)  
- Video URLs / IDs referencing publicly available YouTube sources  
- Instructions for using the annotation files  

### ❌ What is **not** included:
- Raw video files  
- Any private download links  
- Any redistributed identifiable video data  

### ⚠️ Important Notes:
- All videos originate from **public YouTube sources**  
- Researchers **must retrieve videos independently**  
- Usage must comply with:
  - YouTube’s Terms of Service  
  - Institutional ethics approval  
  - Local copyright and data protection laws  
- Some videos may no longer be available due to removal by the original uploader  

Due to **ethical approval and legal restrictions**, we **cannot share or redistribute the raw video dataset**.

✅ You are welcome to freely use the **clinical annotation files** provided in this repository for research.

## Conditions of Data Use  
Data annotations are avilable and can be used as per licence  
[Licence Information](https://github.com/Rahmyyy/GAVD?tab=MIT-1-ov-file#readme)

## Dataset Features  
<img src="figures/gavd_features_summary.png" alt="GAVD Dataset Features" width="600"/>

<img src="figures/Example Gait Category Numbers2.png" alt="Gait Subclasses" width="600"/>

<img src="figures/gavd_gait_classes.png" alt="GAVD Subclass Classification" width="600"/>

<img src="figures/person-centric.png" alt="Camera View Annotations" width="600"/>

## Data Structure  
Data is provided as pkl files part 1 to 5 or csv files part 1 to 5.

| *Data Column* | *Description* |
|:-------------:|:-------------:|
| seq       | sequnce ID unique to a section of gait in single direction |
| frame_num | corresponding frame number of video |
| cam_view  | Annotated person-centric view |
| gait_event| clinically annotated gait event (NOTE: this is limited in this current dataset) |
| dataset   | general classificaiton of normal and abnomral gait |
| gait_pat  | clinically annotated classification of gait from observation by clinican |
| bbox      | bounding box values tracking indiviuals gait |
| vid_info  | video related metadata |
| id        | video youtube id |
| url       | url to access video |

<img src="figures/GAVD_data_sample.png" alt="Example GAVD Annotation Data Structure" width="900"/>

## Citation  
Please use the following citation if you find our work uesful:

```bibtex
@ARTICLE{Ranjan2025,
  author={Ranjan, Rahm and Ahmedt-Aristizabal, David and Ali Armin, Mohammad and Kim, Juno},
  journal={IEEE Access}, 
  title={Computer Vision for Clinical Gait Analysis: A Gait Abnormality Video Dataset}, 
  year={2025},
  volume={13},
  number={},
  pages={45321-45339},
  doi={10.1109/ACCESS.2025.3545787}}

