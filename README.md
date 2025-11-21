<!-- title -->
<!-- <div align='center'>
    <img src="icons/TSBOW_icon_white_border.png" alt="TSBOW icon" width="50">
</div> -->

<h1 align='center'>
    TSBOW – Traffic Surveillance Benchmark for Occluded Vehicles
    Under Various Weather Conditions
</h1>


<!-- MARK: authors -->
<div align='center'>
    <a href="https://scholar.google.com/citations?user=pCTUkWwAAAAJ">
        Ngoc Doan-Minh Huynh</a> &emsp;
    <a href="https://scholar.google.com/citations?user=crRQGUAAAAAJ">
        Duong Nguyen-Ngoc Tran</a>  &emsp;
    <a href="https://scholar.google.com/citations?user=xPyle9AAAAAJ">
        Long Hoang Pham</a>     
</div>

<div align='center'>
    Tai Huu-Phuong Tran &emsp;
    Hyung-Joon Jeon     &emsp;
    Huy-Hung Nguyen     &emsp;
    Duong Khac Vu       &emsp;
    Hyung-Min Jeon      
</div>

<div align='center'>
    Son Hong Phan       &emsp; 
    Quoc Pham-Nam Ho    &emsp;
    Chi Dai Tran        &emsp;
    Trinh Le Ba Khanh   &emsp;
    <a href="https://scholar.google.com/citations?user=9z0SfKoAAAAJ">
        Jae Wook Jeon</a>
</div>


<!-- affliation -->
<div align='center'>
    <a href="https://micro.skku.ac.kr/micro/index.do">Automation Lab</a>, Sungkyunkwan University
</div>


<!-- MARK: URLs -->
<!-- get img shields at: -->
<!-- https://shields.io/badges -->
<!-- check icon at: -->
<!-- https://github.com/simple-icons/simple-icons/blob/master/slugs.md  -->
<br> 
<div align="center">
  <a href="https://skkuautolab.github.io/TSBOW/"><img src="https://img.shields.io/static/v1?label=TSBOW&message=Website&color=fa9f1b" style="height: 25px;"></a>  
  <a href="https://aaai.org/conference/aaai/aaai-26/"><img src="https://img.shields.io/static/v1?label=Main_Paper&message=AAAI&color=green" style="height: 25px;"></a>  
  <a href="https://aaai.org/conference/aaai/aaai-26/"><img src="https://img.shields.io/static/v1?label=Supplementary&message=arXiv&color=FF0066&logo=arxiv" style="height: 25px;"></a>  
  <a href="https://github.com/SKKUAutoLab/TSBOW"><img src="https://img.shields.io/static/v1?label=Code&message=Github&color=6699FF&logo=github" style="height: 25px;"></a>   
  <a href="https://huggingface.co/datasets/skku-autolab/TSBOW/tree/main"><img src="https://img.shields.io/static/v1?label=Dataset&message=HuggingFace&color=FF6600&logo=huggingface" style="height: 25px;"></a>  
</div>
<br>

(UPDATING....) 

(All links would be updated on the conference day.)


![TSBOW Dataset Scenes](images/Figure_All_Scenes.png)


## 🎉NEWS

<!-- + [2026.01.20] 🎆 TSBOW dataset is available on HuggingFace. -->
<!-- + [2025.12.31] 🔥 Our paper, code and TSBOW dataset are released! -->
+ [2025.11.11] 🔥 Our code and TSBOW website are released!

## Abstract

Global warming has intensified the frequency and severity of extreme weather events, which degrade CCTV signal and video quality while disrupting traffic flow, thereby increasing traffic accident rates. Existing datasets, often limited to light haze, rain, and snow, fail to capture extreme weather conditions. To address this gap, this study introduces the Traffic Surveillance Benchmark for Occluded Vehicles under Various Weather Conditions (TSBOW), a comprehensive dataset designed to enhance occluded vehicle detection across diverse annual weather scenarios. Comprising over 32 hours of real-world traffic data from densely populated urban areas, TSBOW includes more than 48,000 manually annotated bounding boxes and 3.2 million semi-labeled boxes, spanning eight traffic participant classes from large vehicles to micromobility devices and pedestrians. We establish an object detection benchmark for TSBOW, highlighting challenges posed by occlusions and adverse weather. With its varied road types, scales, and viewpoints, TSBOW serves as a critical resource for advancing Intelligent Transportation Systems. Our findings underscore the potential of CCTV-based traffic monitoring, paving the way for new research and applications. The TSBOW dataset is available at: https://github.com/SKKUAutoLab/TSBOW.



## Overview

| Statistics | Value |
|--------|:-------:|
| 📹 **Processed Videos** | 198 |
| ⏱️ **Duration** | 32 hours |
| 🖼️ **Total Frames** | 3.2M |
| 🏷️ **Semi-Annotated Instances** | 71.1M |
| ✏️ **Manual-Annotated Frames** | 48K |
| 📦 **Manual-Annotated Instances** | 1.1M |


## Dataset Download

We provide scripts to download the TSBOW dataset from HuggingFace. Please refer to the [`download_TSBOW.py`](utils/download_TSBOW.py) script for more details.

**Contact for dataset**: {ngochdm, duongtran, phlong}@skku.edu


## References

Thanks to the developers and contributors of the following open-source repositories, whose invaluable work has greatly inspire our project:

- [X-AnyLabeling](https://github.com/CVHub520/X-AnyLabeling): An open-source tool for precise bounding box creation.
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics): Detection models for training and real-time inferencing.
- [YOLOv12](https://github.com/sunsmarterjie/yolov12): A model for object detection.

Our repository is licensed under the **Apache 2.0 License**. However, if you use other components in your work, please follow their license.


## Citation

**If our research is helpful to you, please cite our paper using the following BibTeX format**

```bibtex
@article{Huynh_TSBOW_AAAI_2026,
    title   = {TSBOW: Traffic Surveillance Benchmark for Occluded Vehicles Under Various Weather Conditions},
    author  = {Ngoc Doan-Minh Huynh, Duong Nguyen-Ngoc Tran, Long Hoang Pham, Tai Huu-Phuong Tran, Huy-Hung Nguyen, Trinh Le Ba Khanh, Chi Dai Tran, Duong Khac Vu, Son Hong Phan, Quoc Pham-Nam Ho, Hyung-Min Jeon, Hyung-Joon Jeon, Jae Wook Jeon},
    journal = {AAAI 2026},
    year    = {2025}
}
```


<!-- ![Star History Chart](https://api.star-history.com/svg?repos=SKKUAutoLab/TSBOW&type=Date) -->

<div align="center"><a href="#top">🔝 Back to Top</a></div>