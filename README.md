# Black Ice Detection Dataset

![Dataset Examples](images/dataset_examples.png)

## Dataset Statistics

### 1. Train, Valid, Test Data Distribution

**Table x. 데이터셋 별 Train, Valid, Test 데이터 개수**
| Dataset | Train | Valid | Test |
|---------|-------|-------|------|
| White | 413 | 0 | 0 |
| Black | 814 | 0 | 0 |
| OD | 1137 | 325 | 162 |

### 2. Annotation Details

**Table x. Annotation Details**
| Metric | White | Black | OD |
|-------------------------------------|---------|---------|---------|
| Number of Annotations | 437 | 2819 | 2417 |
| Average Annotations per Image | 1.1 | 3.5 | 1.5 |
| Average Proportion of Instance Pixel Area | 3.16% | 12.37% | 12.34% |
| Average Image Brightness | 149.358 | 123.028 | 56.575 |

### 3. Annotations per Image

**Bar Graph: Annotations per Image**
![Fig x. White 데이터셋 Annotations per Image](images/ObjCount_w.png) ![Fig x. Black 데이터셋 Annotations per Image](images/ObjCount_b.png) ![Fig x. OD 데이터셋 Annotations per Image](images/ObjCount_OD.png)

### 4. Annotation Heatmaps

**Heatmap: Annotation Locations**
![Fig x. White 데이터셋 Annotation Heatmap](images/heatmap_w.png) ![Fig x. Black 데이터셋 Annotation Heatmap](images/heatmap_b.png) ![Fig x. OD 데이터셋 Annotation Heatmap](images/heatmap_OD.png)

### 5. Distribution of Pixel Proportion and Brightness

**Bar Graphs: Pixel Proportion and Brightness**

- <img src="images/PixelArea_W.png" alt="Fig x. White 데이터셋 Pixel Proportion" width="300"/>
- <img src="images/brightness_w.png" alt="Fig x. White 데이터셋 Brightness Distribution" width="300"/>
- <img src="images/PixelArea_B.png" alt="Fig x. Black 데이터셋 Pixel Proportion" width="300"/>
- <img src="images/brightness_B.png" alt="Fig x. Black 데이터셋 Brightness Distribution" width="300"/>
- <img src="images/PixelArea_OD.png" alt="Fig x. OD 데이터셋 Pixel Proportion" width="300"/>
- <img src="images/brightness_OD.png" alt="Fig x. OD 데이터셋 Brightness Distribution" width="300"/>

## Usage

- **Download:** The dataset can be freely downloaded from Zenodo using the following DOI: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10428765.svg)](https://doi.org/10.5281/zenodo.10428765).

## Cameras

- iPhone SE2 (Apple, California)
- iPhone SE3 (Apple, California)
- iPhone 12 (Apple, California)
- iPhone 14 Pro (Apple, California)
- Q9 (LG Electronics, Seoul, Korea)
- V30 (LG Electronics, Seoul, Korea)
- Tello (DJI, ShenZhen, China)
