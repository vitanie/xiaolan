# 小蓝--中文交互式智能家居机器人(在树莓派raspberrypi上运行)
![Code主要语言](https://img.shields.io/badge/main_code-python-blue.svg)
![Version版本](https://img.shields.io/badge/last_version-V1.0-green.svg)
![build编写进度](https://img.shields.io/badge/first_ver-26%25-brightgreen.svg)
![QQ](https://img.shields.io/badge/QQ-1481605673-yellow.svg)


这是一个中文的智能家居控制对话机器人——由叮当衍生而来，目前还未100%完成，所以发上来，希望大家一起研发，一个人研发也没那么多点子和经验

- 对不起！因为我只是一个刚上初一的小孩，所以如果有任何觉得使用不方便或者错误的地方，希望多多谅解
- 如果大家有点子的话，加我QQ：1481605673，我真诚的邀请您成为小蓝的开发者

## 唤醒词问题：
- 由于本机器人的语音唤醒引擎是snowboy的
- 所以唤醒词英文的会比较准确，所以使用了唤醒词blueberry，比以前的中文唤醒词要好得多，翻译过来就是蓝莓，也没有脱离主题
- 但是snowboy的唤醒词是越多人训练则越准确，所以希望大家在使用小蓝的同时，打开下面的snowboy训练连接，只需要录制三次音频即可
- 网址：https://snowboy.kitt.ai/hotword/20710 （记得录音时说blueberry）
## 介绍本开源项目和WIKI请看：
### https://github.com/xiaoland/xiaolan-dev/wiki
![服务架构](https://github.com/xiaoland/xiaolan-dev/blob/master/%E5%B0%8F%E8%93%9D%E6%9C%8D%E5%8A%A1%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE.PNG)

## 更新：（有时间先后顺序）
- 注意：旧的更新在xiaolan-dev，这里是小蓝-1
- 小蓝添加可配置性，设置文件在setting.py
- 小蓝欢迎音改为用户名+欢迎语（用户名在设置文件里配置)
- 加快运行速度，百度token只需请求一次（直到一个月后过期）
