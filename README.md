# playmusicbox
音乐播放器

### 技术
* HTML+CSS使用
* 原生JS使用：dom操作、事件操作（绑定、监听）
* Ajax使用（数据的获取、数据的处理）
* HTML5音乐API的运用

### 功能实现

* 音乐数据

(1) music.json 模拟后台数据
(2) 基本音乐信息数据展示：包括歌曲真实外链地址、歌名、歌手名、配图 

* 播放页面功能

(1) 点击功能，使其开始、暂停

(2) 自动播放功能，上一首播完下一首自动播放

(3) 前进、后退功能，开启上一首、下一首功能

(4) 可拖动进度条功能,随意切换进度长度

(5) 进度时间功能，展示播放时间

(6) 歌图切换功能，展示一歌对应一图


* 获取数据的方式

（1） 静态服务器，+写好的json数据文件

（2） 部署到githubpages

（3） Mock数据方式：手写一个server，根据路由返回任意格式的数据，不仅限于json


* 几个音乐api接口：（在mdn找到对应的）



* 如何对音乐的地址操作：
对象.属性（方法）


### 遇到问题及解决

* 问题1：music.json的路径问题

解决：去掉 ‘/ ’之后可以正常查看进程

* 问题2：跨域的问题  

解决：由于本地运行产生下载一个sublimeserver的线上预览插件，解决跨域问题，以及http改为https

* 问题3：网络异常的问题

解决：个人使用流量热点

* 问题4： http-server启动项目文件问题

解决：npm重装nodejs

* 问题5：音乐外链的选择：

解决：
首先，使用通用公式：将下面ID数字换成网易云播放页面的id即可
如：http://music.163.com/song/media/outer/url?id=ID数字.mp3  

然后，歌曲展示：金莎 最后一个夏天
http://music.163.com/song/media/outer/url?id=247557

### 收获
* 收获1：由于要将作品推github，使用Git推库更熟练
* 收获2：因为跨域的产生，表面了解前后端分离的重要性
 
