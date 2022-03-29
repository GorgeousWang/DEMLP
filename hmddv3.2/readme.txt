diseases.txt #疾病的idx
mirnaslist.txt #基因的idx表示
alldata_delete.txt #官网原始的删除冗余信息的基因疾病关联数据，
#包含 35547 miRNA-disease association entries which include 1206 miRNA genes, 894 diseases from 19280 papers #注意，官网给出的是1206个基因和893条边，有错误，经过多次查验，且查看官方的索引列表得知，共有894条边

asso_idx_list.txt #存储用idx表示的基因疾病关联


asso_idx_list_as_one_honmegraph.txt #将整个网络作为一整个网络来处理
mirna_disease_idex.txt #上述文件中的所有节点对应的mirna或者疾病