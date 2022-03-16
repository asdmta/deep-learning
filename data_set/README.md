## 这个文件夹是用来存放训练样本的目录
花数据集下载链接为：http://download.tensorflow.org/example_images/flower_photos.tgz

1，将压缩包解压到date_set下文件夹flower_data下，里面有五个花的类别
3，回到data_set，在pycharm中执行"split_data.py"脚本自动将数据集划分成训练集train和验证集val    划分比例为 9/1
4，最后得出目录如下：
flower_data   
  ── flower_photos（解压的数据集文件夹，3670个样本）  
     ── train（生成的训练集，3306个样本）  
       ── val（生成的验证集，364个样本） 
```