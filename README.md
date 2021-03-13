# intellivision_clustering

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mrsndmn/intellivision_clustering/blob/main/Clustering.ipynb)

[Пожатые дескрипторы и ноутбук](https://drive.google.com/drive/folders/1-D4VfBQ43bvDfjDRc9IlA6Ecqfn2m0Ll)


| Descriptor    |  Size | Method          | calinski_harabasz_score | davies_bouldin_score | cluster interpretation |
| ---           | ---   | ---             | ---                     | ---                  | ---                     |
| osnet         | 200   | MiniBatchKMeans |  23471                  | 2.7                  | by color |
| osnet         | 200   | DBSCAN euclidean|  45                     | 2.9                  | no |
| osnet         | 200   | DBSCAN cosine   |  20                     | 9.1                  | no |
| efficient net | 200   | MiniBatchKMeans |  111654                 | 1.8                  | no |
| efficient net | 200   | DBSCAN euclidean|  588                    | 3.5                  | no |
| efficient net | 200   | DBSCAN cosine   |  376                    | 3.1                  | no |
| vdc_color     | 128   | MiniBatchKMeans |  111654                 | 1.82                 | by color |
| vdc_type      | 200   | MiniBatchKMeans |  119597                 | 1.6                  | by type |


----

##### Лучший алгоритм кластеризации MiniBatchKMeans на дескрипторах osnet

[Метки кластеров](osnet_MiniBatchKMeans.csv)

![resources/osnet/osnet.gif](resources/osnet/osnet.gif)

# todo примеры

----

##### Худший алгоритм DBSCAN и худшие дескрипторы efficient net

![resources/effnet/effnet.gif](resources/effnet/effnet.gif)

# todo примеры
