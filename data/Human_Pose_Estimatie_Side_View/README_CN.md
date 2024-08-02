# README.md
- en [English](README.md)
- zh_CN [简体中文](README_CN.md)

  # 人体姿态估计 - 侧视角

我们的数据集是从互联网上的比赛视频记录中收集的。这段视频片段是奥运会跳远比赛的助跑部分，完全由一台侧向摄像机拍摄。

与正面人体相比，现有模型在估计人体的横向姿势方面明显不那么有效。所以我们提出了这个数据集。

下图是使用YOLOv8姿势的视频。此任务具有估计不准、左右误差和遮挡等挑战。

![image](https://github.com/zhiSports/AI_Sports_Dataset/blob/main/data/Human_Pose_Estimatie_Side_View/img/raw.gif)

下图是是我们重新标注过后的视频。

![image](https://github.com/zhiSports/AI_Sports_Dataset/blob/main/data/Human_Pose_Estimatie_Side_View/img/re.gif)

我们的数据集总共包含42段视频片段，总计3650帧。
