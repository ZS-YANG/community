> 1. 原则上请使用中文。
> 2. 侧重阐述设计思路而不只是实现方案细节，体现对方案选型的利弊考量（必要的需要有预调研实验数据支撑），特别是对框架和用户两个维度的影响。
> 3. 多利用图表来阐述设计思路。

# 标题

|任务名称 | 154 论文复现：YOLOv6 v3.0: A Full-Scale Reloading | 
|---|---|
|提交作者<input type="checkbox" class="rowselector hidden"> | 德尔塔大雨淋 | 
|提交时间<input type="checkbox" class="rowselector hidden"> | 2023-3-7 | 
|版本号 | 此设计文档的版本号，如V1.0 | 
|依赖飞桨版本<input type="checkbox" class="rowselector hidden"> | 如无特殊情况，都应基于develop版本开发 | 
|文件名 | 提交的markdown设计文档文件名称，如：20230307_design_template.md<br> | 

# 一、概述
## 1、相关背景

参考repo https://github.com/meituan/YOLOv6

## 2、功能目标
- s版本COCO数据集精度37.5mAP
- 完成复现后合入PaddleYOLO

## 3、意义
- 集中阐述本次升级的作用和意义。
- 对于需要预调研数据支撑的需要依据预调研结论给出量化预估。

# 二、飞桨现状
对飞桨框架目前支持此功能的现状调研，如果不支持此功能，是否有其他可绕过的方式.


# 三、业内方案调研
描述业内深度学习框架如何实现此功能，包括与此功能相关的现状、未来趋势；调研的范围包括不限于TensorFlow、PyTorch、NumPy等。

# 四、对比分析
对第三部分调研的方案进行对比**评价**和**对比分析**，论述各种方案的优劣势。

# 五、设计思路与实现方案

## 1、主体设计思路与折衷
### 整体全貌（可选）
请附上飞桨框架整体架构图，并标明本设计在其中的位置，以及本方案实施后整体框架图的变化，并附对应描述。
### 主体设计具体描述
请画出本方案核心部分的功能设计及逻辑架构图，并附对应描述。并需要列出方案所包含的各模块及分别在代码库的哪些部分进行修改。
### 主体设计选型考量
必须时需要预调研实验支撑。

## 2、关键技术点/子模块设计与实现方案
逐点列出。对每个技术点/子模块要有清晰描述，不要只附参考文献。涉及数据结构、接口设计的要明确列出对应方案，修改或新增代码的位置。每一点若有多种实现可能的，请特别列出选型考量因素（必须时需要预调研实验支撑）。

## 3、主要影响的模块接口变化
### 请列出核心设计对应的直接接口变化
### 请逐一排查对对框架各环节的影响
包括不限于网络定义、底层数据结构、OP、数据IO、执行、分布式、模型保存、预测部署各环节的影响。如没有影响也要注明。

# 六、测试和验收的考量
自测方案，CE，目标达成验收的度量方式。

# 七、影响面
需要进一步讨论的问题，开放性问题，有争议问题；对其他模块是否有影响。
## 对用户的影响

## 对二次开发用户的影响
新增的哪些功能和API会暴露给二次开发用户。
## 对框架架构的影响
## 对性能的影响
## 对比业内深度学习框架的差距与优势的影响
## 其他风险

# 八、排期规划
时间和开发排期规划，主要milestone。

# 名词解释

# 附件及参考资料
