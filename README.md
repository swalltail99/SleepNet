# 基于人体生理数据的睡眠分层研究


# 毕业设计

## 介绍
略
## 2. 研究背景
睡眠对于人类的健康和幸福感非常的重要。睡眠质量直接影响人身体的诸多方面，比如记忆，免疫力，荷尔蒙分泌以及新陈代谢 [^1]。

[^1]: Cirelli, Chiara, and Giulio Tononi. "Is sleep essential?." PLoS biology 6.8 (2008): e216.

## 3. 数据集（DataSet）
本研究所采用的数据集为开源医学生物信号研究网站[PhysioNet](www.physionet.org)在2018年举办的“You Snooze You Win”睡眠生理信号处理竞赛。数据集收集了1985组实验对象，所有样本数据都经过马塞诸塞总医院(Massachusetts General Hospital, MGH)的计算生理学临床实验室(Computational Clinical Neurophysiology Laboratory, CCNL)进行睡眠障碍诊断。数据分为训练集(training sets, n = 994)和测试集(testing sets, n = 989)。MGH对数据的睡眠阶段进行了注释，包括以下六个睡眠阶段：清醒、第一阶段、第二阶段、第三阶段、快速眼动(REM)和其他，在数据中以30s的时间间隔被注释。

数据包含了睡眠过程中各种各样的生理信号，包括：脑电图(EEG)、眼电图(EOG)、肌电图(EMG)、心电图(EKG)和上静脉血氧饱和度(SaO2)。所有信号采样到200hz，并以微伏为单位进行测量。

## 4. 预期实验算法安排（Methods & Experiment)
### 4.1 支持向量机(SVM)

### 4.2 卷积神经网络(CNN)

### 4.3 循环神经网络（RNN）

### 4.4 睡眠评价(Sleep Scoring)——CNN与LSTM



