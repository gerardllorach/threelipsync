# ThreeLS - threelipsync

计算实时音频流中三个混合形状（接吻、闭嘴和张嘴/下巴）的权重。该算法通过简单的方程计算三个频率带的能量，并将它们映射到混合形状上。

要使用麦克风，请调用startMic()。要使用来自URL的外部音频文件，请使用startSample(URL)。请记住，网页应为https，以便使用麦克风。

有关算法背后理论的解释，请参见此处：
https://www.youtube.com/watch?v=89pBiGKXpZI

这是Unity的软件包：
https://doi.org/10.5281/zenodo.5765691

参考文献：
Llorach，G.，Evans，A.，Blat，J.，Grimm，G.和Hohmann，V.，2016年9月。基于Web的实时语音驱动唇同步。在2016年第8届国际游戏和虚拟世界应用会议（VS-GAMES）（第1-4页）。 IEEE。

Unity驱动参考地址：
https://zenodo.org/records/5765692
