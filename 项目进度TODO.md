# 毕设项目进度TODO
## 参考项目学习
### 总结分类
|项目名称|使用的数据集|备注|
|----|----|----|
|AmongtheSleep-Master| 2018Challenge |参考代码很多，很乱|
|CNN+LSTM| Sleep-EDFx， CCSHS|只有训练完的h5参数模型，无训练代码，论文为硕士学位论文，年份为2017|
|EEG_classification(DeepSleepNet)|MASS,Sleep-EDF|代码齐全。很乱，需要仔细查看，论文为期刊，年份为2017|
|MultitaskSleepNet|MASS,Sleep-EDF|代码很多，需要看论文理解，论文为期刊，年份：2019年|
|Physionet2018挑战|2018challenge挑战数据集|论文很多，有一个提交的代码，可以去比赛网页找找是否有公开所有代码|
|SiameseNet|2018挑战赛数据集|有论文，有代码|

### 数据集信息

|数据集名称|下载网址|描述|备注|
|----|----|----|----|
|PhysioNet Challenge 2018|https://physionet.org/content/challenge-2018/1.0.0/|采样率200 Hz|很大，大概200多G|
|Sleep-EDFx|https://physionet.org/content/sleep-edfx/1.0.0/|采样率100 Hz|已下载|

#### SleepNetEdx
**数据整体介绍**

> The sleep-edf database contains 197 whole-night PolySomnoGraphic sleep recordings, containing EEG, EOG, chin EMG, and event markers. Some records also contain respiration and body temperature. Corresponding hypnograms (sleep patterns) were manually scored by well-trained technicians according to the Rechtschaffen and Kales manual, and are also available.

数据包涵197个人的整晚生理信号数据，包括EEG(Electroencephalogram,脑电图)，EOG（electro-oculogram，眼电图），chin EMG(颏肌电图)等数据。这些数据都被专业的人士通过手动进行过睡眠分层。

**数据特点**

每个人的数据已经经过专业人士的处理。睡眠的模式被分成W, R, 1, 2, 3, 4, M(Movement time)和?(not scored).

> The *PSG.edf files are whole-night polysmnographic sleep recordings containing EEG (from Fpz-Cz and Pz-Oz electrode locations), EOG (horizontal), submental chin EMG, and an event marker. The SC*PSG.edf files (see the 'sleep cassette study') often also contain oro-nasal respiration and rectal body temperature.

> The *Hypnogram.edf files contain annotations of the sleep patterns that correspond to the PSGs. These patterns (hypnograms) consist of sleep stages W, R, 1, 2, 3, 4, M (Movement time) and ? (not scored). All hypnograms were manually scored by well-trained technicians (identified by the eighth letter of the hypnogram filename) according to the 1968 Rechtschaffen and Kales manual [3], but based on Fpz-Cz/Pz-Oz EEGs instead of C4-A1/C3-A2 EEGs, as suggested by [4]).

所有EOG，EMG和EEG信号的采样率都为100Hz

> EOG, EMG and EEG signals were sampled at 100 Hz, and the event marker at 1 Hz. The physical marker dimension ID+M-E relates to the fact that pressing the marker (M) button generated two-second deflections from a baseline value that either identifies the telemetry unit (ID = 1 or 2 if positive) or marks an error (E) in the telemetry link if negative. Subjects and recordings are further described in the file headers, the descriptive spreadsheet ST-subjects.xls, and in [1].

#### PhysioNet Challenge 2018数据

数据已经有专业的人士处理过，被分为六个阶段，分别为W, S1, S2, S3, REM和未知。

> The sleep stages of the subjects were annotated by clinical staff at the MGH according to the American Academy of Sleep Medicine (AASM) manual for the scoring of sleep. More specifically, the following six sleep stages were annotated in 30 second contiguous intervals: wakefulness, stage 1, stage 2, stage 3, rapid eye movement (REM), and undefined.

所有的信号都为200Hz采样率。

> The subjects had a variety of physiological signals recorded as they slept through the night including: electroencephalography (EEG), electrooculography (EOG), electromyography (EMG), electrocardiology (EKG), and oxygen saturation (SaO2). Excluding SaO2, all signals were sampled to 200 Hz and were measured in microvolts. For analytic convenience, SaO2 was resampled to 200 Hz, and is measured as a percentage.

## 文献代码阅读 List

|项目名称|使用的数据集|阅读计划|
|----|----|----|
|EEG_classification(DeepSleepNet)|MASS,Sleep-EDF|未完成|
|CNN+LSTM| Sleep-EDFx， CCSHS|未完成|
|MultitaskSleepNet|MASS,Sleep-EDF|未完成|
|Physionet2018挑战|2018challenge挑战数据集|未完成|
|SiameseNet|2018挑战赛数据集|未完成|

[ x ] DeepSleepNet: a Model for Automatic Sleep Stage Scoring based on Raw Single-Channel EEG.
[ ] Automatic Sleep Stage Classification using Convolutional Neural Networks with Long Short-Term Memory.
[ ] Joint Classification and Prediction CNN Framework for Automatic Sleep Stage Classification.








