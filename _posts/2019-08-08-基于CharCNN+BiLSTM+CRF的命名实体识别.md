---
categories: NLP
tags: 命名实体识别
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
前些日子报名了[“达观杯”文本智能信息抽取挑战赛](https://www.biendata.com/competition/datagrand/), 使用官方提供的Baseline, 也就是纯CRF, 跑出的准确率为85.0%。

将深度学习融入CRF有很多模型, 如:LSTM+CRF、BiLSTM+CRF、CharCNN+BiLSTM+CRF等。
今天来尝试下 **CharCNN+BiLSTM+CRF**, 实验代码取自[SLTK](https://github.com/liu-nlper/SLTK)。
