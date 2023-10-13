# Tag-basedRecommendationWorkspace
Tag-basedRecommendation
推荐算法实验结果

这个仓库包含了四个不同推荐算法的实验结果，分别是SimpleTagBased、TagBasedTFIDF、TagBasedTFIDF_Improved以及ExtendTagBased。每个实验包括10次运行以获取平均结果。

## SimpleTagBased实验

- 运行时间: 404.88秒
- 平均结果 (M=10, N=10):
    - Precision: 0.337
    - Recall: 0.553
    - Coverage: 3.361
    - Diversity: 0.7914
    - Popularity: 2.3397

## TagBasedTFIDF实验

- 运行时间: 443.55秒
- 平均结果 (M=10, N=10):
    - Precision: 0.352
    - Recall: 0.58
    - Coverage: 16.952
    - Diversity: 0.883
    - Popularity: 1.3244

## TagBasedTFIDF_Improved实验

- 运行时间: 551.44秒
- 平均结果 (M=10, N=10):
    - Precision: 0.163
    - Recall: 0.267
    - Coverage: 19.411
    - Diversity: 0.8612
    - Popularity: 0.7859

## ExtendTagBased实验

- 运行时间: 430.87秒
- 平均结果 (M=10, N=10):
    - Precision: 0.344
    - Recall: 0.566
    - Coverage: 3.415
    - Diversity: 0.7904
    - Popularity: 2.3363

这些实验结果可用于比较不同基于用户标签的推荐算法的性能和特征。每个算法都有其独特之处，根据特定应用的需求，可以选择合适的算法来实现个性化推荐系统。
