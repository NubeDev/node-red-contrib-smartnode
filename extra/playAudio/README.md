###音乐播放节点

本节点用于播放上传的音乐。

####配置参数
1. Name：节点名字。

####输入
1. msg.payload：播放的音乐序号(从0开始）以及关闭音乐。

####输出
无

####使用方法
1. 使用前，使用文件上传功能上传要播放的音乐（目前仅支持wmv和mp3格式的音乐）。
2. 点击 **+file list** 增加播放项目，并选择音乐文件。
3. 程序部署后，可以通过输入序号播放相应的音乐，或者输入**-1**结束播放。

###PlayAudio

This node can be used to play audio file.

####Config
1. Name：Name of node。

####Input
1. msg.payload：The audio file index(start from 0), or stop palying(-1)。

####Output
None

####HowTo
1. Please upload the audio file before you use this node.