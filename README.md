# Apple visio Pro--visionOS微信小程序

化腐朽为神奇，把不可能变成了可能，这是生成式人工智能的独特魅力。

借助AIGC，现在对于普通人而言，可以做的事更多了。比如，挑战写一段段代码，打造属于自己网站、小程序。

百闻不如一见，实践出真知。经过多次的Github、CSDN搜索，并结合相关AI大模型，我终于完成了人生中的第一个小程序——“Vision Pro模拟”。

![image](https://github.com/fireflyrqh/visio/assets/27807431/5ca37db6-40b1-4dec-847c-19672724da27)

该小程序主要利用后置摄像头，获取实时的物理世界作为背景，基于混合现实的场景下，模拟苹果Vision Pro的操作系统VisionOS的基本界面。

![image](https://github.com/fireflyrqh/visio/assets/27807431/be36d747-c407-41c4-8073-f69ef468c7b5)


功能方面，目前2.7版本主要有一些Demo可以简单体验，包括TV、Music、今天吃什么、天气、网速测试、韦特塔罗、色盲测试、相册、留言板等。受限于手机竖版尺寸，部分元素并不能很好地迁移到手机上去查看，仅供参考。


这次的小程序制作主要是结合了kimi、ChatGPT3.5、通义灵码三个大语言模型制作而成。因为有时候一个模型给出的代码可能在真正落地输出的时候，并不能达成理想的效果，所以需要多个AI辅助，以达成理想的设计。

AIGC的 Prompt参考：

请你扮演一个微信小程序专业程序猿，不能说不会，也不能说只能提供建议，要给出具体的代码。请按照下方需求设计一个完整，可用的微信小程序，包括wxml、wxss、js、json等文件代码：(接下来，写下自己具体的需求)。


实际上，这个微信小程序的设计想法是来源于github@Jaykef，他制作了一个基于web界面的VisionOS设计，基于此灵感，我扩展到了微信小程序上。不过，由于手机与PC的长宽比问题，微信小程序的界面设计要更小一些，删除了很多东西。才得以在手机小程序上看到。由于暂无商业变现能力，产品本身也没有什么价值，暂不做Android和iOS的兼容。


github@Jaykef的web程序教程：

克隆仓库

git clone https://github.com/Jaykef/Vision-Pro-webOS.git
在根目录中安装节点模块

npm install
运行应用程序

node server.js
在http://localhost:3000/尝试应用程序


