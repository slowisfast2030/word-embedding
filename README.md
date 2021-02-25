# word-embedding
学习目标
- 学习词向量的概念
- 用Skip-thought模型训练词向量
- 学习使用PyTorch dataset和dataloader
- 学习定义PyTorch模型
- 学习torch.nn中常见的Module
    - Embedding
- 学习常见的PyTorch operations
    - bmm
    - logsigmoid
- 保存和读取PyTorch模型
    

第二课使用的训练数据可以从以下链接下载到。

链接:https://pan.baidu.com/s/1tFeK3mXuVXEy3EMarfeWvg  密码:v2z5

在这一份notebook中，我们会（尽可能）尝试复现论文[Distributed Representations of Words and Phrases and their Compositionality](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)中训练词向量的方法. 我们会实现Skip-gram模型，并且使用论文中noice contrastive sampling的目标函数。


