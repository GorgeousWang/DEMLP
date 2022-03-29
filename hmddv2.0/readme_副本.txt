edge.txt #融合包括基因相似度和疾病相似度的关联网络
label.txt #包含了基因和疾病结点的标签

my_process中是我自己处理好的文件，其中：
onlyknowndiseasemirnainteraction.txt #用整个网络表示的基因和疾病的关联 495miRNA 383diseases 共5300对关联
directedonlyknowndiseasemirnainteraction.txt #代表以有向图的形式存储图，即10600条边

#原始处理好的数据源自论文IMCMDA
# 1-4四个文件夹为原始数据，其中含有weighted的相似度文件是原作者计算用的，可以不管。