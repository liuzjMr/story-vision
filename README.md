<!--
 * @Author: Sanfor Chow
 * @Date: 2024-01-31 03:53:52
 * @LastEditors: Sanfor Chow
 * @LastEditTime: 2024-04-16 17:46:07
 * @FilePath: /story-vision/README.md
-->

## 功能设计
总体>main.py

1、提取分镜场景: 小说文本分句、SD生成图片和TTS文本转语音(带时间)

2、小说内容>推导提示词(SD绘画)

3、图片音频合并视频

模型:

TTS(edge)、SD绘画模型(这里使用:cetusMix_Whalefall2)、GPT(这里使用Gemini)

## 后续改进

SD人物保持一致role

视频合并时画面转变效果、字幕等

## 输出效果
SD图片生成
![SD图片生成](https://github.com/zhousanfu/story-vision/blob/main/data/img/第1章%20进局子了_1.jpg?raw=true)

输出视频
[输出视频](https://github.com/zhousanfu/story-vision/raw/main/data/video/第1章%20进局子了_out.mp4)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zhousanfu/story-vision&type=Date)](https://star-history.com/#zhousanfu/story-vision&Date)
