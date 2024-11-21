[CSBasicKnowledge/src/SUMMARY.md at main · CS-BAOYAN/CSBasicKnowledge (github.com)](https://github.com/CS-BAOYAN/CSBasicKnowledge/blob/main/src/SUMMARY.md)



# Github的使用

#### 0.1 环境配置

创建仓库

·首先在Github上new一个repo

·打开Git Bash

```
$ ssh-keygen -t rsa -C "470789405@qq.com"
```

·然后到对应路径下寻找密钥，打开id_rsa，然后复制里面的内容

![image-20240405160504750](C:\Users\张丰凯\AppData\Roaming\Typora\typora-user-images\image-20240405160504750.png)

·在Github的账号的settings中，找到SSH key，复制进去

·回到Git Bash，输入

```
$ ssh -T git@github.com
```

·设置账号名和邮箱

```
$ git config --global user.name "heishuini"
$ git config --global user.email "xxx@qq.com"
```



#### 0.2 仓库克隆到本地

·存储到本地的位置

```
cd /D/GitHubRepo
```

·克隆文件

git bash中 

  Ctrl+ins  复制   Shift+ins 粘贴

```
git clone SSH地址（如git@github.com:heishuini/studyRoute.git）
```

#### 0.3 上传代码

·ls 查看文件

·git add “file_name” ,引号里面是你所要上传的文件名称，添加到暂存区

·git commit -m “描述内容，备注” 从暂存区添加到仓库

·git push origin master（或者是main）



删除仓库

点击仓库-> settings -> 拉到最下面delete



## 1.Academic 学术

- 谷歌学术：Google Scholar [[en](https://scholar.google.com/)]
- 计算机科学文献数据库：DBLP [[en](https://dblp.org/)]
- SCI期刊查询和scihub各种科研导航: [[Page](https://www.ablesci.com/journal)]
- ACM数字图书馆：ACM Digital Library [[en](https://dl.acm.org/)]
- IEEE学术数据库：IEEE Xplore [[en](https://ieeexplore.ieee.org/)]
- SCI论文检索：Web of Science [[en](https://www.webofscience.com/)]
- EI论文检索：Engineering Village [[en](https://www.engineeringvillage.com/)]
- 中文文献检索：中国知网 [[zh-cn](https://www.cnki.net/)]
- 中国计算机学会（CCF）推荐国际学术会议和期刊目录（2022版）[[pdf](https://github.com/CS-BAOYAN/CSBasicKnowledge/blob/main/CCF_Recommended_List.pdf)]
- CCF会议投稿截止时间汇总：[[zh-cn](https://ccfddl.github.io/)]
- CCFrank: 在相关网站的搜索结果中显示 CCF 评级的浏览器插件 [[Github](https://github.com/WenyanLiu/CCFrank4dblp)] [[Chrome](https://chrome.google.com/webstore/detail/ccfrank/pfcajmbenomfbjnbjhgbnbdjmiklnkie)] [[Edge](https://microsoftedge.microsoft.com/addons/detail/pboigbpepikdoeindehghnpojjblhjmm)] [[FireFox](https://addons.mozilla.org/zh-CN/firefox/addon/ccfrank/)]
- 清华大学计算机学科推荐学术会议和期刊列表 (TH-CPL) [[Github](https://github.com/bugaosuni59/TH-CPL)]
- CSRankings: Computer Science Rankings [[en](https://csrankings.org/)]
- 国家自然科学基金查询 [[zh](https://kd.nsfc.gov.cn/resultInit)]

## 2.CS

[如何使用这本书 - CS自学指南 (csdiy.wiki)](https://csdiy.wiki/使用指南/)  主要是各种CS专业课理论知识 + 领域内容



[计算机教育中缺失的一课 · the missing semester of your cs education (missing-semester-cn.github.io)](https://missing-semester-cn.github.io/)



[1c7/Crash-Course-Computer-Science-Chinese: :computer: 计算机速成课 | Crash Course 字幕组 (全40集 2018-5-1 精校完成) B站播放量 383万 (github.com)](https://github.com/1c7/crash-course-computer-science-chinese)



[Quick Reference & Quick Reference](https://quickref.cn/)  各种软件的应用速查表



## 3.AI

结合自学指南学习。[如何使用这本书 - CS自学指南 (csdiy.wiki)](https://csdiy.wiki/使用指南/) 

### 3.1 机器学习

入门

[fengdu78/Coursera-ML-AndrewNg-Notes: 吴恩达老师的机器学习课程个人笔记 (github.com)](https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes?tab=readme-ov-file)

[(强推|双字)2022吴恩达机器学习Deeplearning.ai课程_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Pa411X76s/?spm_id_from=333.337.search-card.all.click&vd_source=62c6b20b70c91e96b6a69bd5e1f914a8)

**Tom Mitchell**：

**Tom**定义的机器学习是，一个好的学习问题定义如下，他说，一个程序被认为能从经验**E**中学习，解决任务**T**，达到性能度量值**P**，当且仅当，有了经验**E**后，经过**P**评判，程序在处理T时的性能有所提升。



[Vay-keen/Machine-learning-learning-notes: 周志华《机器学习》又称西瓜书是一本较为全面的书籍，书中详细介绍了机器学习领域不同类型的算法(例如：监督学习、无监督学习、半监督学习、强化学习、集成降维、特征选择等)，记录了本人在学习过程中的理解思路与扩展知识点，希望对新人阅读西瓜书有所帮助！ (github.com)](https://github.com/Vay-keen/Machine-learning-learning-notes)

机器学习公式推导

[datawhalechina/pumpkin-book: 《机器学习》（西瓜书）公式详解 (github.com)](https://github.com/datawhalechina/pumpkin-book)

机器学习训练时的调整策略

[deeplearning-ai/machine-learning-yearning-cn: Machine Learning Yearning 中文版 - 《机器学习训练秘籍》 - Andrew Ng 著 (github.com)](https://github.com/deeplearning-ai/machine-learning-yearning-cn?tab=readme-ov-file)

[CS 229 - 机器学习技巧和秘诀速查表 (stanford.edu)](https://stanford.edu/~shervine/l/zh/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks#model-selection)



### 3.2 深度学习

深度学习清单

[aymericdamien/TopDeepLearning: A list of popular github projects related to deep learning](https://github.com/aymericdamien/TopDeepLearning?tab=readme-ov-file)

理论部分

[d2l-ai/d2l-zh: 《动手学深度学习》：面向中文读者、能运行、可讨论。中英文版被70多个国家的500多所大学用于教学。 (github.com)](https://github.com/d2l-ai/d2l-zh?tab=readme-ov-file)

[qiaohaoforever/DeepLearningFromScratch: 《深度学习入门：基于Python的理论与实现》电子版及配套代码。 (github.com)](https://github.com/qiaohaoforever/DeepLearningFromScratch)



[dragen1860/Deep-Learning-with-PyTorch-Tutorials: 深度学习与PyTorch入门实战视频教程 配套源代码和PPT (github.com)](https://github.com/dragen1860/Deep-Learning-with-PyTorch-Tutorials)

项目部分

[hzy46/Deep-Learning-21-Examples: 《21个项目玩转深度学习———基于TensorFlow的实践详解》配套代码 (github.com)](https://github.com/hzy46/Deep-Learning-21-Examples?tab=readme-ov-file)

Tensorflow教程

[fendouai/Awesome-TensorFlow-Chinese: Awesome-TensorFlow-Chinese，TensorFlow 中文资源精选，官方网站，安装教程，入门教程，视频教程，实战项目，学习路径。QQ群：167122861，公众号：磐创AI，微信群二维码：http://www.tensorflownews.com/ (github.com)](https://github.com/fendouai/Awesome-TensorFlow-Chinese?tab=readme-ov-file)

Pytorch手册

[zergtant/pytorch-handbook: pytorch handbook是一本开源的书籍，目标是帮助那些希望和使用PyTorch进行深度学习开发和研究的朋友快速入门，其中包含的Pytorch教程全部通过测试保证可以成功运行 (github.com)](https://github.com/zergtant/pytorch-handbook)

Pytorch实战

[深入浅出PyTorch — 深入浅出PyTorch (datawhalechina.github.io)](https://datawhalechina.github.io/thorough-pytorch/)

#### 3.2.1 CV(Computer Vision)

入门

[【公开课】最新斯坦福李飞飞cs231n计算机视觉课程【附中文字幕】_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1nJ411z7fe/?vd_source=448358f43a4bb5339069f63d9e0b8ac0)



各种注意力机制 最新论文

[MenghaoGuo/Awesome-Vision-Attentions: Summary of related papers on visual attention. Related code will be released based on Jittor gradually. (github.com)](https://github.com/MenghaoGuo/Awesome-Vision-Attentions)



transform架构的CV 最新论文   transformer:一种采用注意力机制的深度学习模型

[Yangzhangcst/Transformer-in-Computer-Vision: A paper list of some recent Transformer-based CV works. (github.com)](https://github.com/Yangzhangcst/Transformer-in-Computer-Vision)



MMDetection:基于Pytorch的目标检测开源工具箱

[open-mmlab/mmdetection: OpenMMLab Detection Toolbox and Benchmark (github.com)](https://github.com/open-mmlab/mmdetection?tab=readme-ov-file)



图像分割

Segment anything Model(SAM) Meta新发布的模型

[facebookresearch/segment-anything: The repository provides code for running inference with the SegmentAnything Model (SAM), links for downloading the trained model checkpoints, and example notebooks that show how to use the model. (github.com)](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file)



VLM 视觉语言 最新论文和模型

[jingyi0000/VLM_survey: Collection of AWESOME vision-language models for vision tasks (github.com)](https://github.com/jingyi0000/VLM_survey)

[DirtyHarryLYL/LLM-in-Vision: Recent LLM-based CV and related works. Welcome to comment/contribute! (github.com)](https://github.com/DirtyHarryLYL/LLM-in-Vision)



#### 3.2.2 NLP(自然语言处理)

入门

[【双语字幕】斯坦福CS224n《深度学习自然语言处理》课程(2019) by Chris Manning_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Eb411H7Pq/?vd_source=448358f43a4bb5339069f63d9e0b8ac0)

入门

[zibuyu/research_tao: NLP研究入门之道 (github.com)](https://github.com/zibuyu/research_tao?tab=readme-ov-file)

几乎最全的中文NLP资源库

https://github.com/fighting41love/funNLP  

最新进展（涵盖各国语言）

[sebastianruder/NLP-progress: Repository to track the progress in Natural Language Processing (NLP), including the datasets and the current state-of-the-art for the most common NLP tasks. (github.com)](https://github.com/sebastianruder/NLP-progress/tree/master?tab=readme-ov-file)



### 3.3 CUDA介绍

[CUDA C++ Programming Guide (nvidia.com)](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)



## 4.获取数据集

[数据集-OpenDataLab](https://opendatalab.com/)



## 5.大语言模型 LLM

相关介绍

[RUCAIBox/LLMSurvey: The official GitHub page for the survey paper "A Survey of Large Language Models".](https://github.com/RUCAIBox/LLMSurvey/tree/main?tab=readme-ov-file)



[liguodongiot/llm-action: 本项目旨在分享大模型相关技术原理以及实战经验。 (github.com)](https://github.com/liguodongiot/llm-action)



## 6.AIGC相关

ChatGPT

[yzfly/awesome-chatgpt-zh: ChatGPT 中文指南🔥，ChatGPT 中文调教指南，指令指南，应用开发指南，精选资源清单，更好的使用 chatGPT 让你的生产力 up up up! 🚀 (github.com)](https://github.com/yzfly/awesome-chatgpt-zh?tab=readme-ov-file#与-chatgpt-高效对话prompt工程指南)

Prompt（编程，绘画，写作）

[phodal/understand-prompt: 【🔞🔞🔞 内含不适合未成年人阅读的图片】基于我擅长的编程、绘画、写作展开的 AI 探索和总结：StableDiffusion 是一种强大的图像生成模型，能够通过对一张图片进行演化来生成新的图片。ChatGPT 是一个基于 Transformer 的语言生成模型，它能够自动为输入的主题生成合适的文章。而 Github Copilot 是一个智能编程助手，能够加速日常编程活动。](https://github.com/phodal/understand-prompt?tab=readme-ov-file)

各种专业知识的ChatGPT

[Open Prompt - Create, Use, Share ChatGPT prompts.](https://openprompt.co/)

AI工具（文本，编程，图像，视频，音频，）

[ZhikangNiu/awesome-ai-tools: A curated list of Artificial Intelligence Top Tools (github.com)](https://github.com/ZhikangNiu/awesome-ai-tools?tab=readme-ov-file)

## 7.必知必会

[nosuggest/Reflection_Summary: 算法理论基础知识应知应会 (github.com)](https://github.com/nosuggest/Reflection_Summary)

## 8.科研经验

[pengsida/learning_research: 本人的科研经验 (github.com)](https://github.com/pengsida/learning_research)

## 9.迁移学习

所有资料内容。

[jindongwang/transferlearning: Transfer learning / domain adaptation / domain generalization / multi-task learning etc. Papers, codes, datasets, applications, tutorials.-迁移学习 (github.com)](https://github.com/jindongwang/transferlearning)

## 
