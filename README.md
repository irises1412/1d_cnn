# 1d_cnn
用来处理一维数据的cnn
1.在lenet5基础上修改完成 
2.具体就是输入时为二维数据，[BATCH_SIZE, LENGTH],LENGTH为一维数据的长度
3.输入后，因为tf输入维四维张量，所以卷积前和池化前将数据扩展为四维，计算后再压缩回二维
4.全连接层单元个数还是按照原模型没有修改
5.参数还未经调优
