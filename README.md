# CNN-SQL
实验环境
Win10 8G内存
NVIDIA GeForce GTX 850M
Python 环境：python3.5,tensorflow ,gensim,keras等包。

先运行word.py对数据进行预处理，数据存放目录data。
cnn.py对数据进行训练，得到检测模型。
test1.py对验证集进行测试，可在test.py中修改所选用的模型的进行测试。
proxy_v2.py为简单的代理模块，可作为代理对真实环境进行测试，只需修改ip与端口即可。只能用于简单测试，代理模块还未优化好。
