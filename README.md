根据《Attention Is All You Need》、Annotated Transformer源代码以及我的理解实现一个最简Transformer模型，并实现中英翻译任务。

模型架构	  4层/256d/8头	完全复现
训练稳定性	Loss 10→3 稳定下降
翻译质量	  3/4 句子语义正确
BLEU 分数	  10.05	
代码完整性	数据加载→训练→推理全流程
