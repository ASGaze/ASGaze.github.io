<style>
.markdown-body h1 {
    border-bottom: none
}
.markdown-body h2 {
    border-bottom: 2px solid grey;
}
.markdown-body {
    border-bottom: 2px solid black;
    padding-left: 65px !important;
    padding-right: 65px !important;
    box-shadow: 5px 2px 2px grey;
    background: white;
}
body {
    background: #c1bebe;
}
</style>
<div>
    <br><br><br>
    <h1 style="text-align:center;"><b>ASGaze: Gaze Tracking on Any Surface with Your Phone</b></h1>
<!--     <p style="font-size:20px;text-align:center;"><b>Improving Non-Cooperative Iris Tracking</b></p> -->
</div>



## **Overview**

In this project, we introduce ASGaze, a new gaze tracking system designed using the common RGB camera from mobile phones. In addition to improving the accuracy of existing RGB camera-based gaze tracking methods, a novelty of ASGaze is that it can be configured to track gaze points on various surface areas commonly required in different applications, such as mobile phone screens, computer displays or even non-electronic surfaces like whiteboards or paper - a situation that is difficult for existing RGB camera-based methods to handle. To achieve the design of ASGaze, we revisit the 3D geometric model of the eye, which is widely adopted by high-end and commercial gaze trackers, and it has the potential to achieve our design goals. To avoid the high cost of commercial solutions, we identify three key issues to be addressed when processing the eye model with an RGB camera, including how to first accurately extract eye iris boundary that is the meta-information in our gaze tracking design, and then how to remove gaze ambiguity from iris boundary to gaze point transformation, and finally how to precisely map gaze points to the target tracking surface. In this paper, we propose a series of effective techniques to address these issues. We develop a prototype system and conduct extensive experiments on three different typical tracking surfaces to show promising performance gains compared to the recent solution.

## Demo Video

<div align="center">       
    <a href="https://youtu.be/_4NIigLkK0k">      
        <img src="http://img.youtube.com/vi/_4NIigLkK0k/0.jpg"        
             alt="Everything Is AWESOME"        
             style="width:50%;">       
    </a>     
</div>
<div align="center">       
    <a href="https://youtu.be/zfvWCtT1FkI">      
        <img src="http://img.youtube.com/vi/zfvWCtT1FkI/0.jpg"        
             alt="Everything Is AWESOME"        
             style="width:50%;">       
    </a>     
</div>
<div align="center">       
    <a href="https://youtu.be/0VlgbBK_ewU">      
        <img src="http://img.youtube.com/vi/0VlgbBK_ewU/0.jpg"        
             alt="Everything Is AWESOME"        
             style="width:50%;">       
        </a>     
</div>

## Publication

**Gaze Tracking on Any Surface with Your Phone**

**Jiani Cao**, Chengdong Lin, Yang Liu, Zhenjiang Li

ACM SenSys, 2022

<a href="https://dl.acm.org/doi/10.1145/3560905.3568544">[Paper]</a>  <a href="https://github.com/Jiani-CAO/ASGaze">[Code]</a>  <a href="https://jiani-cao.github.io/slides/2022-SenSys-ASGaze-slides.pdf">[Slides]</a>

## Citation

If you find our work useful in your research, please consider citing:

```
@inproceedings{cao2022gaze,
title={Gaze Tracking on Any Surface with Your Phone},
author={Cao, Jiani and Lin, Chengdong and Liu, Yang and Li, Zhenjiang},
booktitle={Proceedings of the 20th ACM Conference on Embedded Networked Sensor Systems},
pages={320--333},
year={2022}
}
```



