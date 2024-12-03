---
layout: page
title: 光之刺绣
description: 柔性发光材料在传统手工艺中的应用
img: assets/img/Embroidery/title.jpg
importance: 1
category: Design Projects
---

2024  
*Teamwork: **Ziqi Liu**, Yao Lu, Xuezhu Wang*  
*Advisor: Haipeng Mi*  
<br>
这项工作是与[梅赛德斯-奔驰，北京](https://group.mercedes-benz.com/careers/about-us/locations/location-detail-page-5184.html)的合作项目的一部分。在这个项目中，我们探索了新兴智能材料在汽车内饰中的应用形式和交互设计，包括纺织传感器、智能材料、4D材料和动态材料。

在这项工作中，我们探讨了[一种新型柔性发光材料](https://www.nature.com/articles/s41586-021-03295-8)在传统**刺绣**技术中的潜在应用，以及它在汽车座舱交互中的可能用途。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/overview.gif" title="example image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## 图样设计与小样制作

我们设计了三种不同类型的图案，包括功能性图案、传统刺绣图案和传统编织图案。此外，我们还使用传统的刺绣和编织技艺，利用柔性发光材料制作了刺绣样品。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/f1.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/f2.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/f3.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/f4.png" title="example image" class="img-fluid rounded" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/e1.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/e2.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/e3.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/e4.png" title="example image" class="img-fluid rounded" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/w2.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/w3.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/w4.png" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/w5.png" title="example image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## 光效控制和电路实现

由于需要高电压、低电流的交流电源驱动，我们选择将柔性发光材料与场效应晶体管（FET）串联与电源连接，并使用ESP32控制器来调节线材的亮度。
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/circuit.jpg" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/circuit1.jpg" title="example image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## 汽车内饰设计与实施

我们设计并制作了一个用于梅赛德斯-奔驰工程车内饰的发光刺绣装饰，随后将其安装在实际车辆中进行效果预览。这为未来进一步探索互动功能提供了可行性探索。

由于保密协议的限制，最终结果暂时无法展示。不过，在此我们展示了一些设计过程中的图片。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/design.jpg" title="example image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    草图绘制
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/animation.jpg" title="example image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    光效设计
</div>


<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/install1.jpg" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Embroidery/install2.jpg" title="example image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    组装现场
</div>

