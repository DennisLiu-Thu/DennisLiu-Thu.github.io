---
layout: page
title: COMETIC
description:  通过基于光标的互动隐式校准增强智能手机眼动追踪
img: assets/img/COMETIC/title.jpg
importance: 1
category: Research Projects
---

2024  
*Chang Liu, Xiangyang Wang, Chun Yu, Yingtian Shi, Chongyang Wang, **Ziqi Liu**, Chen Liang, Yuanchun Shi*  
<br>
智能手机上的眼动追踪准确性有限，限制了其应用。现有的基于RGB摄像头的眼动追踪系统依赖于大量的数据集，而这些数据集可以通过利用用户交互中隐式收集的校准数据进行持续微调来改进。在此背景下，我们提出了COMETIC（Cursor Operation Mediated Eye-Tracking Implicit Calibration，基于光标操作的眼动追踪隐式校准），它引入了一种基于光标的交互方式，并利用光标与眼动之间的内在关联。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/chi25b-sub8820-i14.mp4" autoplay="true" controls="true" width="100%" height="auto" %}
    </div>
</div>

<br>
## 智能手机上的眼动追踪 

当前智能手机眼动追踪面临两个主要挑战：对个体用户的个性化支持有限，以及难以适应频繁的姿势变化。为了解决这些问题，我们开发了一种通过隐式用户交互动态校准眼动追踪的系统，从而提高了准确性和个性化。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/background.png" title="image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## COMETIC  

通过将有效的光标坐标作为注视真实值的代理，并结合相应的图像对眼动追踪模型进行微调，COMETIC在交互过程中提高了准确性。过滤和微调过程都利用了预训练模型，并且可以通过个性化的、动态更新的数据进一步提升性能。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/teaser.png" title="image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    COMETIC的工作流
</div>
<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/interaction.gif" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/algorithm.png" title="image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    COMETIC的交互和模型架构
</div>


<br>
## 数据收集实验  

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/apparatus.jpg" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/experiment_layout.png" title="image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    数据收集实验的设备和界面
</div>


<br>
## 评估  

结果表明，COMETIC实现了平均眼动追踪误差为208.04像素（1.2厘米），相比于未进行微调的系统提高了49.64%。分析还显示，过滤光标点时，当实际注视距离在250到300像素（1.44到1.73厘米）之间时，能够获得最佳的眼动追踪效果。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_video_to_gaze_error.png" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_cursor_video_to_distance_precision.png" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_cursor_video_to_distance_fp_error.png" title="image" class="img-fluid rounded" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_iter_gaze_error.png" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_iter_precision.png" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_iter_fp_error.png" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/COMETIC/0829_iter_gaze_error_of_subject_tau_250.png" title="image" class="img-fluid rounded" %}
    </div>
</div>
