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

### 安装方法一：手动

* 安装上(下)班打卡
	* 点击触动精灵左上角新建脚本, 任意命名。如：『钉钉上(下)班打卡』
	* 将项目 `punch-in(out)/main.lua` 文件内容粘贴到脚本中
	* 设置定时运行时间, 如：8：50 (18: 01)
	* 建议上下班多设置几个打卡时间段，以防漏打！
	
### 安装方法二：扫码

* 上班打卡

![上班打卡二维码](./punch-in/qrcode.png)

* 下班打卡

![下班打卡二维码](./punch-out/qrcode.png)

### 已测试软件版本

| 钉钉  | 触动精灵 | 手机 |
|:------------- |:---------------:| -------------:|
| v3.5.0+      | v2.2.5 |         SM-N900 |
| v3.5.0+      | v2.2.5 |         GT-i9300 |
| v3.5.0+      | v2.2.5 |         Redmi 4 |
