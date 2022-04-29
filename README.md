# BERT预训练

目前支持RoBERTa和GPT模式的预训练。请在tensorflow 1.14或1.15下运行。

## 使用
```
python data_utils.py # 生成tfrecord
python pretraining.py # 启动预训练过程
```

## 语料库
1. CBLUE 数据集
2. 医学电子书 https://github.com/scienceasdf/medical-books
