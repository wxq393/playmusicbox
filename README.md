## 一、项目名 playmusicbox
音乐播放器

### 二、功能展示
1.音乐数据
(1) music.json 模拟后台数据
(2) 基本数据的格式展示：歌曲真实外链地址、 

2. 播放页面功能
(1) 点击功能，使其开始、暂停
(2) 自动播放功能，上一首播完下一首自动播放
(3) 前进、后退功能，开启上一首、下一首功能
(4) 进度条功能,随意切换进度长度
(5) 进度时间设置，展示播放时间
(6) 歌图切换功能，


### 三、技术栈
1.HTML+CSS3使用

2.原生JS使用

3.绑定点击事件的运用

4.html5音乐API的运用

### 四、遇到问题及解决
- 问题1：music.json的路径问题  
解决：去掉 ‘/ ’之后可以正常查看进程

- 问题2：跨域的问题  
解决：由于本地运行产生下载一个sublimeserver的线上预览插件，解决跨域问题，以及http改为https

- 问题3：网络异常的问题  
解决：个人使用流量热点

- http-server启动项目文件问题——重装解决

- 音乐外链的选择：

通用公式：将下面ID数字换成网易云播放页面的id即可
http://music.163.com/song/media/outer/url?id=ID数字.mp3  

如：金莎 最后一个夏天
http://music.163.com/song/media/outer/url?id=247557

### 五、收获
- 收获1：由于要将作品推github，使用Git推库更熟练
- 收获2：因为跨域的产生，表面了解前后端分离的重要性
 

