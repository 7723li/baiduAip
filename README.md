语音播报实现过程

0.选择到识别页面->

1.PyAduio录音成wav格式(命名为record.wav)->

2.百度语音识别，获取文字结果（语音文字）->

3.根据文字结果执行程序，如 "天气" ，执行墨迹天气爬虫->

4.百度语音合成，将爬虫结果生成（result.mp3）->

5.显示爬虫结果->

6.PyAduio播放 result.mp3。

运行前先编译c文件，输出exe文件，然后双击exe文件就可以
