---
layout: page
title:  AI-Assisted Art Training
description: AI 辅助艺术训练
img: assets/img/AI-assisted/title.jpg
importance: 3
category: Research Projects
---

在专业艺术创作（如书法和绘画）中，学习成本高且资源有限，顶级资源稀缺。尽管AIGC可以生成艺术作品作为审美参考，但它对创意技能的培养并没有提供太多指导。从人机协作的角度出发，我们的目标是让AI不仅能够生成艺术作品，还能像人类一样“创造”艺术，指导艺术技能的学习。  
本项目将开发一个多模态系统，捕捉指尖压力和笔姿等数据，创建专业数据集，并利用表征学习提供互动式的专家反馈。  

该项目目前处于初期阶段，相关的研究和数据收集平台的开发已经完成。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/overview.jpg" title="image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## 研究方向与内容  

鉴于艺术创作的复杂性，我们将从书法练习开始。通过与专业书法家的讨论，我们确定了笔尖压力和姿势是关键因素。我们的目标是专注于建模书法练习过程中笔尖压力和笔姿的变化，用于模型训练和教学系统的开发。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/copybook.jpg" title="image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## 数据收集系统开发  

通过研究，我们发现像Apple Pencil这样的商业产品可以提供必要的数据，如笔尖压力和笔姿。因此，我们计划首先使用从Apple Pencil收集的数据验证其可行性。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/applepencil.jpg" title="image" class="img-fluid rounded" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/penbrushfinetune.jpg" title="image" class="img-fluid rounded" %}
    </div>
</div>

我们开发了一款基于Apple Pencil的书法练习应用，包含四种不同的书法模板。该应用在用户书写过程中记录关键信息，如触点位置、时间戳、笔尖压力、笔倾斜角度和方向角度，并以JSON格式保存。

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/font.png" title="image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/interface.png" title="image" class="img-fluid rounded" %}
    </div>
</div>

<br>
## 数据处理与模型训练

在完成初步的数据对齐、过滤和可视化后，我们计划使用自回归方法训练模型，以理解这些顺序模式。我们的初步计划是通过遮掩某些数据点并重新生成它们来训练模型。该项目目前正在进行中，后续进展将定期更新。

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI-assisted/masking.png" title="image" class="img-fluid rounded" %}
    </div>
</div>