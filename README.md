## AI双擎-微信智能客服
内置[Deepseek](https://platform.deepseek.com/api_keys)官方API及[阿里百炼Deepseek API](https://bailian.console.aliyun.com/?tab=model#/api-key)，AI服务不可用时无缝自动切换，全天持续稳定运行！

本工具通过RPA自动化实现，不访问私有接口，快来使用吧~


## 使用方式
### 安装鸿鹄RPA 
下载并安装[鸿鹄RPA https://hhrpa.com/](https://hhrpa.com/)，支持windows7~11

> 部分杀毒软件会误报，一律允许即可

![安装鸿鹄RPA](/images/hh-download.png)

### 导入 微信客服.hha 文件
![导入 微信客服.hha 文件](/images/import.png)

### 打开编辑窗口
![打开编辑界面](/images/editor.png)

### 配置
双击调用流程，在弹窗中添加配置
* 群或者联系人白名单：只自动回复指定的群或者联系人，每行一个，可以有多行
* 资料或者问答数据：投喂给AI的数据，AI会根据文档内容回复。把准备好的文档粘贴（Ctrl+V）到这即可，文档字数建议5万字以内，最好不要超过10万字
* BAILIAN_API_KEY：阿里百炼官网申请的API KEY  [https://bailian.console.aliyun.com/?tab=model#/api-key](https://bailian.console.aliyun.com/?tab=model#/api-key)
* DEEPSEEK_API_KEY：Deepseek官网的API KEY [https://platform.deepseek.com/api_keys](https://platform.deepseek.com/api_keys)

填写完成后点击 确定 按钮

> BAILIAN_API_KEY和DEEPSEEK_API_KEY至少要填写一个，建议两个都填写，当其中一个访问失败时会自动访问另一个。

![配置](/images/config.png)

### 打开微信电脑版并置顶 文件传输助手
搜索 文件传输助手，右击选择置顶
![置顶](/images/top.png)

> 微信只支持3.9版本，其他版本未测试

![微信版本](/images/wchat-version.png)

### 开始自动回复
点击 `主流程`，然后点击`运行`按钮。当收到消息后就可以自动回复了
> 点击运行按钮后请`不要`操作鼠标及键盘，否则会干扰运行。如果您没有空闲的电脑可以在虚拟机中运行。

![智能回复](/images/run.png)

### 效果视频
![视频](/videos/ai-wchat.mp4)