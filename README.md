# ChatGPT Private使用说明  
喜欢的同学可以点个Star谢谢

### 一、声明：
### 1）本网站仅可用于学习知识查阅资料。
### 2）本网站不会有任何广告，也不会以任何形式存储用户相关的任何信息，访问本站也无需科学上网工具。
### 3）本网站源自github开源项目，在此项目上做了一些小调整，需要源码的同学可以自行浏览学习。https://github.com/Yidadaa/ChatGPT-Next-Web

### 二、使用说明，输入网址http://39.100.77.240/#/
#### 1）点击登录按钮
![7939858b70462f2b8444f94d8ea90a2](https://github.com/Enbuly/pencil/assets/15280614/30d484e0-33bf-4bfa-9c8b-b12d587a74aa)
#### 2）输入您的api key点击确定
![67b2a8141d024a62e711215d44a15a2](https://github.com/Enbuly/pencil/assets/15280614/9ad862b5-c284-408d-9327-508da0d4df94)
#### 3）正常使用演示
![1805f25b18133c0362a7337ddca826f](https://github.com/Enbuly/pencil/assets/15280614/e5e6f9cc-1da6-4b52-bffc-63af5aa328b8)

### 三、特别说明
#### 关于api key的获取方式
#### 1）如果你会科学上网，可以在官网自行注册获取。https://platform.openai.com/api-keys
#### 2）如果你不会科学上网，那么可以在某宝购买（搜索关键词api key），一块钱买的账号就能用了，具体自行选择。  
  
  
  
### ---------------------------------我是分割线---------------------------------  
  
# ChatGPT Private本地开发
1、在项目根目录创建.env.local，内容如下  
\# API KEY  
OPENAI_API_KEY=you_api_key  
  
\# 中国大陆用户，可以使用本项目自带的代理进行开发，你也可以自由选择其他代理地址  
BASE_URL=https://gpt.nextapi.fun/api/proxy  

2、安装 nodejs 18 和 yarn。  
3、执行 yarn install && yarn dev 即可。⚠️ 注意：此命令仅用于本地开发，不要用于部署！ 
