<!-- title -->
<h1 align='center'>
    TSBOW – Traffic Surveillance Benchmark for Occluded Vehicles
    <br>Under Various Weather Conditions
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
<!-- <div align="center">
    <br>
    <a href="https://aaai.org/conference/aaai/aaai-26/">Paper</a>  &emsp;&emsp;
    <a href="https://huggingface.co/datasets/skku-autolab/TSBOW/tree/main">Hugging Face Dataset</a>  &emsp;&emsp;
    <a href="https://skkuautolab.github.io/TSBOW/">Website</a>  
</div> -->

<!-- get img shields at: -->
<!-- https://shields.io/badges -->
<!-- check icon at: -->
<!-- https://github.com/simple-icons/simple-icons/blob/master/slugs.md  -->
<div align="center">
  <a href="https://skkuautolab.github.io/TSBOW/"><img src="https://img.shields.io/static/v1?label=TSBOW&message=Website&color=navy"></a>  
  <a href="https://aaai.org/conference/aaai/aaai-26/"><img src="https://img.shields.io/static/v1?label=Main Paper&message=AAAI&color=red"></a>  
  <a href="https://aaai.org/conference/aaai/aaai-26/"><img src="https://img.shields.io/static/v1?label=Supplementary&message=ArXiv&color=green&logo=arxiv"></a>  
  <a href="https://github.com/SKKUAutoLab/TSBOW"><img src="https://img.shields.io/static/v1?label=Code&message=Github&color=blue&logo=github"></a>   
  <a href="https://huggingface.co/datasets/skku-autolab/TSBOW/tree/main"><img src="https://img.shields.io/static/v1?label=Dataset&message=HuggingFace&color=yellow&logo=huggingface"></a>  
</div>
<br>

(UPDATING....) 

(All links would be updated on the conference day.)

## Introduction

![TSBOW Dataset Scenes](images/Figure_All_Scenes.png)

Scenes from the TSBOW dataset, comprising 198 videos recorded across four distinct scenarios spanning all seasons (sunny/cloudy, haze/fog, rain, snow) over a year. The dataset emphasizes adverse weather conditions and densely populated urban areas with heavy traffic, addressing significant challenges in image degradation and vehicle occlusion.

<!-- <video src="videos/road_intersection_conversion.mp4" width="100%" controls></video>-->
<div class="video-container">
    <video controls style="width:100%" autoplay loop playsinline muted>
        <source src="videos/road_intersection_conversion.mp4" type="video/mp4">
        Video Demo: road_intersection
    </video>
</div>

<!-- <video src="videos/specialcases_disaster_conversion.mp4" width="100%" controls></video> -->
<div class="video-container">
    <video controls style="width:100%" autoplay loop playsinline muted>
        <source src="videos/specialcases_disaster_conversion.mp4" type="video/mp4">
        Video Demo: specialcases_disaster
    </video>
</div>

## Overview

| Statistics | Value |
|--------|:-------:|
| 📹 **Processed Videos** | 198 |
| ⏱️ **Duration** | 32 hours |
| 🖼️ **Total Frames** | 3.2M |
| 🏷️ **Semi-Annotated Instances** | 71.1M |
| ✏️ **Manual-Annotated Frames** | 48K |
| 📦 **Manual-Annotated Instances** | 1.1M |

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

## Acknowledgement
