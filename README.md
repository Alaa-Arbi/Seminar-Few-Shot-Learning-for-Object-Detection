# Seminar-Few-Shot-Learning-for-Object-Detection
Few-shot Object Detection (FSOD) is a new research field that has gained a lot of attention because humans are capable of learning discriminative features of new objects from a few samples, while deep learning frameworks still require a large-scale dataset with abundant training samples to achieve reasonable results. In the context of FSOD, a base dataset has abundant annotated instances, while a target dataset has only K annotated instances for each of its N categories (with K being a very small integer, up to 1 in some cases), see figure. FSOD techniques must leverage knowledge gained while training on the base dataset to learn generalizable features from the target dataset without overfitting. As K is very small, plain fine-tuning fails and more spezialized training paradigms must be used. 

<img src="FSOD framework.png" width="128"/>

During this seminar, I presented and explained two of the state-of-the-art frameworks in few-shot learning, namely DeFRCN[[1]](#1) and MetaDETR[[2]](#2). In this repository you can find the report that contains a very detailed explanation of the wokring principles of the selected methodoligies and the slides used during the seminar for explanation.

## References
<a id="1">[1]</a> 
Limeng Qiao, Yuxuan Zhao, Zhiyuan Li, Xi Qiu, Jianan Wu,
and Chi Zhang. Defrcn: Decoupled faster r-cnn for few-shot
object detection, 2021.

<a id="1">[2]</a> 
Gongjie Zhang, Zhipeng Luo, Kaiwen Cui, Shijian Lu, and
Eric P. Xing. Meta-DETR: Image-level few-shot detection
with inter-class correlation exploitation. IEEE Transactions
on Pattern Analysis and Machine Intelligence, pages 1–12,
2022.
