### 钉钉自动考勤
----

问：你们公司打卡么？

答：我在公司不用打卡！

问：你是公司领导吧？好厉害！

答：你们全家都是领导！！我是在公司扔了一个手机，它会自动打卡 (骄傲脸

### 准备
1. 一台android手机，需要root
2. 安装触动精灵android版
3. 当然如果没有钉钉，你现在也不会看到这儿
4. 在钉钉中，工作->考勤打卡->设置->个性化，打开极速打卡
5. 手机必须接入工作wifi，确保极速打卡可以生效

### 手动安装脚本

* 安装上班打卡
	* 点击触动精灵左上角新建脚本, 任意命名。如：『钉钉上班打卡』
	* 将项目 `punch-in/main.lua` 文件内容粘贴到脚本中
	* 设置定时运行时间为每天上班之前半小时内。如：8：50

* 安装下班打卡
	* 点击触动精灵左上角新建脚本, 任意命名。如：『钉钉下班打卡』
	* 将项目 `punch-out/main.lua` 文件内容粘贴到脚本中
	* 设置定时运行时间为每天下班之后半小时内。如：6：10

	
### 扫码安装脚本

* 上班打卡

![上班打卡二维码](./punch-in/qrcode.png)

* 下班打卡

![下班打卡二维码](./punch-out/qrcode.png)

### 已测试软件版本

| 钉钉  | 触动精灵 | 手机 |
|:------------- |:---------------:| -------------:|
| v3.5.0      | v2.2.5 |         三星s3 |
