# thesis-dataset
本人硕士毕业论文使用到的部分实验数据。实验数据为微服务系统的系统架构图结构数据。

实验与研究过程使用python辅助完成。相关数据使用python中的pickle包进行了序列化，查看前请先使用pickle.load()进行反序列化。

所有数据均使用torch_geometric.data 中的HeteroData格式进行保存。每个图结构数据的名称表示各数据截取时段终点的unix时间戳；数据名称只用于做数据区分，数据之间并无优劣之分。

关于torch_geometric，详细信息可参考其官方文档https://pytorch-geometric.readthedocs.io/en/latest/index.html
