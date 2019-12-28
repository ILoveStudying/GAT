# GAT
图神经网络课程——图注意力网络

本github用为图神经网络课程课程大作业，参考代码来自[https://github.com/Diego999/pyGAT/blob/master/](https://note.youdao.com/)

### 说明
1. 参考代码的中只包含cora数据集，对应的数据集在./data/cora下，对应的读取文件为utils.py，测试精度可达到0.847。
2. utils_tf.py是补充的代码，可以读取cora,citeseer,pubmed数据集，对应的数据集在./dataset下，前缀名为ind。利用utils_tf.py测试cora数据集，测试精度可达0.824。
3. 以上两个文件测试的结果不同，原因在于测试集选择的不同，utils.py文件中训练集为0-140，验证集200-500，测试集500-1500。utils_tf.py文件中训练集为0-140，验证集140-640，测试集1708-2707。
