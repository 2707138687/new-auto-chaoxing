# 超星刷课软件（新）

:star: 觉得有帮助的朋友可以给个**Star**

## 更新通知

上传自2022-03-21，可以完成部分超星平台课程，后续将会继续更新
> 由于超星加密方式改变了所以导致部分地方还没有更好的解决方式，如果知道怎么解决的小伙伴可以联系我哦（Issues）！：)

## :smile: 相关项目

[Samueli924/chaoxing web版超星自动化库](https://github.com/Samueli924/chaoxing_web)


## :books: 使用方法

```shell
pip install requests
python main.py 
```

## FAQ(常见问题)

1. 程序相关
    - 问: 程序如何实现完成视频任务点?运行时会有**风险**吗?  
   答: 程序使用从超星AndroidApp中逆向得到的**API发送协议包**完成任务。在超星不更新其API协议的前提下能够**确保安全**  
    - 问: 为什么程序运行时间和实际时间一样，不能**一键瞬间完成**所有任务吗?  
   答: 本程序设计的初衷是在确保**绝对安全**的前提下提高效率，所以在代码中没有添加一键完成所有任务的代码。实际上，一键完成功能十分容易，在Github上已经有许多相关的优秀repo可供下载  
    - 问: 程序用到了哪些第三方库?  
   答: 本程序仅用到了requests库负责完成任务。不同于Github中存在的一些其他使用selenium库的repo，具有内存占用小，带宽占用小的优点  

2. 程序在开发阶段，还有很多问题没有解决，只能部分使用
## :heart: CONTRIBUTORS  
### :one: 感谢[Shanxuns](https://github.com/Shanxuns)修正查找任务点的正则表达式内容 [Pull #33](https://github.com/Samueli924/chaoxing/pull/33)  
### 对于代码有任何问题或建议欢迎Pull&Request  


## :warning: 免责声明  
- 本代码遵循 [GPL-3.0 License](https://github.com/Samueli924/chaoxing/blob/main/LICENSE)协议，允许**开源/免费使用和引用/修改/衍生代码的开源/免费使用**，不允许**修改和衍生的代码作为闭源的商业软件发布和销售**，禁止**使用本代码盈利**，以此代码为基础的程序**必须**同样遵守[GPL-3.0 License](https://github.com/Samueli924/chaoxing/blob/main/LICENSE)协议  
- 本代码仅用于**学习讨论**，禁止**用于盈利**  
- 他人或组织使用本代码进行的任何**违法行为**与本人无关  
