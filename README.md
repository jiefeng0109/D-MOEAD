# Multi-task multi-objective evolutionary network for hyperspectral image classification and pansharpening. [Information fusion 109:102383 (2024)]
This is our official implementation of DMOEAD!

by Xiande Wu, Jie Feng,*, Ronghua Shang, JinJian Wu, Xiangrong Zhang, Licheng Jiao, Paolo Gamba 

# Introduction
## Abstract
Multi-task learning has commonly been used and performed well at joint visual perception tasks. Hyperspectral pansharpening (HP) and hyperspectral classification (HC) tasks extract high-frequency information to enhance edges and classify samples, offering potential for performance improvements in multi-task learning. However, differences between tasks can make it challenging to balance their performances. To address this challenge, this paper proposes a multi-task multi-objective evolutionary network (DMOEAD) for joint learning of HC and HP. A multi-task sufficiency-and-diversity sampling method is designed to unify the heterogeneity of sample construction between two types of tasks. Two types of task-specific networks are constructed to decompose high-frequency information. Further, a collaborative learning module is designed to dynamically learn complementary high-frequency information from another task in different layers. To be compatible with the optimization direction of two types of tasks, multi-task optimization is realized using a deep multi-objective evolutionary algorithm (DMEO). In the DMEO, the set of parameters of the DMOEAD is regarded as an individual. A deep mutation operator is designed and used for network optimization, which accelerates large-scale network parameter searching. The DMEO can coordinate the differences between multiple tasks and provide a set of Pareto network parameter solutions. Finally, the experimental results demonstrate that the proposed method can significantly enhance the performance of both pansharpening and classification tasks.

## Figure.1 Flowchart of the proposed method. 
![image](https://github.com/jiefeng0109/DMOEAD-main/blob/main/1725504747389.jpg)

## 目录

- [数据集描述](#a-namedatasetsa-)
- [用法](#a-nameusagea-)
    - [训练](#a-nameusage-traina-)
    - [测试](#a-nameusage-testa-)
- [试验记录](#a-nameresulta-)


## <a name="datasets"></a> 数据集描述

数据集来自 [Chikusei, 雄安 & Pavia Center]

## <a name="usage"></a> 用法

### <a name="usage-train"></a> 训练

1. 运行DMOEAD-main.py文件

### <a name="usage-test"></a> 测试

验证集等于测试集，无需再另行测试


## Cite
```
@article{wu2024multi,
  title={Multi-task multi-objective evolutionary network for hyperspectral image classification and pansharpening},
  author={Wu, Xiande and Feng, Jie and Shang, Ronghua and Wu, JinJian and Zhang, Xiangrong and Jiao, Licheng and Gamba, Paolo},
  journal={Information Fusion},
  volume={108},
  pages={102383},
  year={2024},
  publisher={Elsevier}
}

```
