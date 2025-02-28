# 通过Python的selenium开发的学习通刷课程序，可自动完成视频、PPT和答题。

**更新日期: 2022-02-04**

---

## 项目背景
在学习Python的时候了解到了selenium库，正好学校要求学生要用学习通，于是萌发了一个自己写刷课程序的想法最终产生了这个项目。  
目前任有些问题无法修复，作者能力有限，如果对项目感兴趣非常欢迎进行交流和提交贡献。
## 项目介绍
### 该项目能够自动完成学习通中视频、PPT和答题等任务，并且保存每个人每个课程的刷课进度。  
1、视频部分，程序能自动播放视频，回答视频中出现的问题。  
2、PPT部分，程序自动识别PPT页数以1秒一页的速度点击PPT。  
3、答题部分，程序自动识别出现的题目，通过查题的API进行答案搜索，自动填写答案，完成后进行保存。  
4、程序能保存多个用户的登陆信息，每位用户单独储存课程进度。启动程序时，程序自动读取当前用户的刷课进度，可以做到随时刷课随时停止。

## 使用
### 该项目依赖：  
>1、selenium（*version3.141.0*）  
2、requests  
3、colorama  

### 项目展示：
1、登陆界面
![demo1](https://github.com/Levitans/XueXiTongAutoFlush/blob/master/demoImage/demo1.png)
2、选择课程
![demo2](https://github.com/Levitans/XueXiTongAutoFlush/blob/master/demoImage/demo2.png)
3、开始刷课
![demo3](https://github.com/Levitans/XueXiTongAutoFlush/blob/master/demoImage/demo3.png)

## 主要项目负责人
**Levitans**
 
## 声明
感谢 https://github.com/destoryD 提供的答案API  
本项目只供对编程感兴趣、喜欢研究的同学来学习和锻炼自己的能力。  
***本项目禁止进行任何商业化***  
***在使用中出现任何意外（如：被官方检测、答题零分等）均由使用者自己承担。***  
**本软件只为学习研究使用，作者不承担任何非法使用本软件造成的法律后果**
