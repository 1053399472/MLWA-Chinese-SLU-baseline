# NOTICE

本仓库基于原论文作者的代码进行修改，主要改动在于将F1值计算由逐词变为SPAN.利用该模型在重新划分好的SMP数据集进行了训练。相关模型已经保存在save目录下，训练的参数同原作者保持一致。

相关结果如下：

| detasets | Slot(F1) | Intent(Acc) | Overall |
| :------: | :------: | :---------: | :-----: |
|   CAIS   |  88.57   |    94.66    |  85.47  |
| SMP2019  |  73.60   |    93.37    |  70.00  |
| SMP2020  |  84.32   |    96.34    |  80.76  |