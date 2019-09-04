# CCL2019-Chinese-Humor-Computation
CCL-2019，中文幽默计算任务的数据集及baseline  

任务说明参见CCL2019官方网站。  
任务每个阶段的排名将在该GitHub公布。  

两个任务取测试集的部分数据构建开发集。  
在比赛的前四个阶段，将根据模型在开发集上的得分对参赛队伍排名。  
完整测试集将在10月5日0时放出，队伍的最终排名由模型在完整测试集上的得分决定。

文件说明：
```、
-- data
    -- task1    # 子任务一：生成幽默识别数据
        -- task1_train.csv    # 训练集
        -- task1_development.csv    # 开发集
    -- task2    # 子任务二：中文幽默等级划分数据
        -- task2_train.csv    # 训练集
        -- task2_development.csv    # 开发集
-- baseline
    -- task1_baseline.ipynb    # 使用LSTM
    -- task2_baseline.ipynb    # 使用LSTM
```
