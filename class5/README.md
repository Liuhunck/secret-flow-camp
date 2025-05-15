# 基于SecretNote项目案例实验

> Author: Liuhunck
>
> Date: 2025.05.15

非学习笔记，记录实验所遇到的问题

- secretflow对水平数据的支持不完善
    - HDataFrame中有很多函数是没有实现的，比如`replace`，而且`apply_func`也不好用
    - 很多回归的模型都不支持HDataFrame，只支持VDataFrame或者FedNdarray，但是FedNdarray也只支持Vertical类型的！导致最后作业没做出来，只实现了数据处理等
- 本次实验的作业要用到HDataFrame，课程上并没有示例，要自己搜查文档](https://www.secretflow.org.cn/zh-CN/docs/secretflow/v1.12.0b0)
- 课后作业设计不太合理（可能是我没做出来的错觉吧 :( ）
- 实验课的作业时间留长点，两个不一定够
- secretnote好像只能开两个结点
- 这个作业对secretnote和secretflow的使用体验不是很好