# CCL2019“小牛杯”中文幽默计算评测
CCL2019，“小牛杯”中文幽默计算任务的数据集及baseline  

任务说明参见CCL2019官方网站：http://www.cips-cl.org/static/CCL2019/call-evaluation.html 。  
任务每个阶段的排名将在该GitHub公布。  

两个任务取测试集的部分数据构建开发集。  
在比赛的前四个阶段，将根据模型在开发集上的得分对参赛队伍排名。  
完整测试集将在10月5日0点放出，队伍的最终排名由模型在完整测试集上的得分决定。

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

第一阶段队伍排名：  

 | 队伍名称 | task1_f1  | task2_macro_f1 | score | rank |
 |:----:|:----:|:----:|:----:|:----:|
 | 我要第一 | 0.8406 | 0.4969 | 0.7031 | 1 |
 | 金山NLP小组 | 0.8531 | 0.3600 | 0.6559 | 2 |
 | 清博AI | 0.8439 | 0.3671 | 0.6532 | 3 |
 | Tenacious Birds | 0.8463 | 0.3417 | 0.6444 | 4 |  
 
