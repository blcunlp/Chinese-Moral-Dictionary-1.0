# 中文道德词典说明文档V1.0
### 1. 中文道德词典资源简介
    中文道德词典是在北京语言大学于东副教授的指导下整理和标注的一个中文道德文本数据资源。  
    该资源将动词、名词、形容词、成语以及汉语的被动表达纳入词典体系中，设计了中文道德词典的理论体系，包含四类标签和四种类型；
    并通过词向量扩展和人工核查的方法，构建了包含25,012个词的中文道德词典资源。  
    构造该资源的宗旨是在伦理计算领域，为中文文本道德判断和倾向性分析提供一个便捷可靠的辅助手段。
    中文道德词典可以用于解决道德分类的问题，同时也可以用于解决一般的倾向性分析问题。  
### 2. 论文链接  
    URL:https://www.aclweb.org/anthology/2020.ccl-1.50
### 3. 格式示例
    中文道德词典中，一般的格式为：

| 词语 | 标签 | 类型 | 备注 |
|:-------:|:----:|:----:|:----:|
| 平权运动 | 1 | 3 | 属性 |
| 马虎 | 0 | 2 | 状态 |
| 盗窃犯 | 2 | 4 | 对象 |
| 被遗弃 | 3 | 1 | 行为 |

### 4. 标签标注
    标签分类按照论文《面向人工智能伦理计算的中文道德词典构建方法研究》所述，分为4类。
    其中，0代表中性，1代表道德，2代表不道德，3代表被动。
### 5. 类型标注
    每个词在每类标签下又进一步标注了其类型。
    其中，1代表事件行为，2代表事件状态，3代表事件属性，4代表事件要素。
    事件要素又再分为地点、对象和媒介。
### 6. 存储及规模
    中文道德词典以XLSX的格式进行存储，含有情感词共25,012个，文件大小为876KB。
