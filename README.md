# hrnet-cls
用hrnet分类网络修改的feature_extraction，输入输出改后与分割网络相同。一共有两个模型，stage3和stage4，stage4显存占用大一些。两个模型共用一组预训练模型和配置文件

与分割网络的区别是分类在imagenet 22k上预训练的，效果可能更好

 hrnet18_stage3/4 里封装的feature_extraction。预训练模型和配置路径在这个文件里
 
 
