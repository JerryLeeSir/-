# 首言
&emsp;&emsp;打标签的精度，会直接影响目标检测算法最终的识别准确率，希望大家要仔细操作。本次采用的数据集为3939张草莓图片，每人操作657张左右。如果连续不停的打标签，600张也就花费2小时左右（亲自实践过）。
下面会详细介绍应该如何操作。
# 压缩包简介
&nbsp;
&emsp;&emsp;首先从群文件下载自己名字对应的压缩包，以我本人的压缩包为例，解压到D盘根目录，注意一定不要解压到桌面（防止有中文路径），也不要解压到其他带有中文的路径的地方。
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111780959-0f4bfa00-88f3-11eb-9dae-cb84cd7d33b3.png)

&nbsp;
&nbsp;
&emsp;&emsp;进入解压后的文件夹后会看到一个VOC数据集和一个labellmg压缩包，首先解压labellmg压缩包到当前目录
# 打标签操作

![image](https://user-images.githubusercontent.com/68058642/111781087-1ffc7000-88f3-11eb-8e3c-1e7b1355bbb3.png)

![image](https://user-images.githubusercontent.com/68058642/111781285-2be83200-88f3-11eb-9e27-acd2822c8c46.png)

&nbsp;
&nbsp;
&emsp;&emsp;进入解压后的labellmg文件夹，找到labellmg程序，鼠标右键，选择管理员身份打开
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111782170-ac0e9780-88f3-11eb-8992-e5df62e7be6b.png)
&nbsp;
&nbsp;
&emsp;&emsp;运行这个程序后，会出现两个窗口，任何一个窗口都不要关闭
![image](https://user-images.githubusercontent.com/68058642/111782220-bc267700-88f3-11eb-881e-f1dd7d679f54.png)
![image](https://user-images.githubusercontent.com/68058642/111782704-4e2e7f80-88f4-11eb-8de6-e9226b35e459.png)
&nbsp;
&nbsp;
&emsp;&emsp;黑窗口，不用管，进入白窗口，首先点击左边第二项Open Dir
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111782816-6f8f6b80-88f4-11eb-8bd6-4fe54da5d946.png)
&nbsp;
&nbsp;
&emsp;&emsp;打开后选择D盘，找到自己的名字，我的是lijiajun（也就是我发给你的文件的解压后的文件夹），选择VOCdevkit,选择VOC2007，选择JPEGImages，最后点击右下角的选择文件夹
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111782867-7fa74b00-88f4-11eb-8aee-1f27a855eadf.png)

&nbsp;
&nbsp;
&emsp;&emsp;之后软件会自动加载，图片
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111782908-8d5cd080-88f4-11eb-8485-7bad9d73bf61.png)

&nbsp;
&nbsp;
&emsp;&emsp;之后点击左边第三项Changes Save Dir，按照下面图片所示顺序选择保存地址
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111782945-9c438300-88f4-11eb-970a-bb811537bc4a.png)

&nbsp;
&nbsp;
&emsp;&emsp;下面简单介绍，布局
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111782993-ae252600-88f4-11eb-9233-b4c0e5f68663.png)

&emsp;&emsp;开始介绍如何开始打标签
&emsp;&emsp;我们在选择好保存地址后，在图片页面按下W键，如果此时界面上出现输入法，按下shift键，之后再按W键，出现如下图所示内容
![image](https://user-images.githubusercontent.com/68058642/111783035-ba10e800-88f4-11eb-9d84-8e68b5cab9bb.png)


&emsp;&emsp;长按鼠标左键，拖动选择草莓区域，再松开鼠标
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783066-c5fcaa00-88f4-11eb-89f2-b587ec63ae3b.png)

&nbsp;
&nbsp;
&emsp;&emsp;松开鼠标后，出现一个选择框，选择Strawberry，再点击ok
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783110-d14fd580-88f4-11eb-9843-67c78ead0892.png)

&nbsp;
&nbsp;
&emsp;&emsp;这样，这张图片的标签我们就打完了，同时按下Ctrl+s保存结果，再按下D键进入下一张图片
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783137-db71d400-88f4-11eb-93f0-f1939d8db234.png)

&nbsp;
&nbsp;
&emsp;&emsp;如果不能一口气处理完所有图片，中途需要关电脑，就需要知道我们处理到哪张图片了，方便之后继续处理，如图所示
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783176-e75d9600-88f4-11eb-8c1a-bc0c10aff009.png)

&nbsp;
&nbsp;
##### &emsp;&emsp;如果你离开的话，一定要记住处理到第几张图片了，为了防止忘记，可以这样，如上图可以知道，我的数据集是从0001972开始的，比如有一天我处理到了0001988（第0001988也处理了），就在群里发一个0001988，下一次直接寻找0001989，点击并进入图片开始处理
&nbsp;
&nbsp;
# 注意事项
1. 如果有事中途离开，软件可以直接关闭
2. 再次进入软件，上述选择路径操作需要重复一遍，他不会记住你之前选择的路径
# 一些解释
&nbsp;
&nbsp;
&emsp;&emsp;每个人的数据集，是随机分配的，类型可能不尽相同
&emsp;&emsp;有抠图类型的，如图所示，这种选择区域的时候可能简单一点
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783231-f6dcdf00-88f4-11eb-8f02-cc6e9c6b6e6d.png)

![image](https://user-images.githubusercontent.com/68058642/111783281-03f9ce00-88f5-11eb-8c36-09d46d637a9b.png)

&nbsp;
&nbsp;
&emsp;&emsp;还有这种的，比较现实的，这种可能辛苦点，一张图片有几个草莓就要打几个标签，不能只打一个
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783318-0eb46300-88f5-11eb-9266-68f3910e5768.png)

![image](https://user-images.githubusercontent.com/68058642/111783370-1e33ac00-88f5-11eb-9797-15b86e36edf7.png)

&nbsp;
&nbsp;
&emsp;&emsp;还有这样的，类似大棚实拍，这种图片很珍贵，一定要好好认真选好草莓的区域进行打标签
&nbsp;
&nbsp;
![image](https://user-images.githubusercontent.com/68058642/111783410-2ab80480-88f5-11eb-9f12-98be8f43afdd.png)

![image](https://user-images.githubusercontent.com/68058642/111783456-35729980-88f5-11eb-8040-914f5744037b.png)

&nbsp;
&nbsp;
&emsp;&emsp;如果还有其他问题，可以在群里问我。
&nbsp;
&nbsp;&nbsp;
&nbsp;
