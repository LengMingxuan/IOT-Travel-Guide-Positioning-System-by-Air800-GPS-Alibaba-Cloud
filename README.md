# IOT-Travel-Guide-Positioning-System BY Air 800
![](https://img.shields.io/badge/Started%20at-19--10--8-blue)
![](https://img.shields.io/badge/Language-lua-blue)
![](https://img.shields.io/badge/Project%20Status-Developing-green)
![](https://img.shields.io/badge/Rely%20on-Air800%2BGPS-blue)
![](https://img.shields.io/badge/Key%20word-Air%20800%20%20%E9%98%BF%E9%87%8C%E4%BA%91%20%20Luat-orange)

# 参考文献： 

[文件类文献:Here to GO](https://github.com/LengMingxuan/IOT_Inf_2019) 

---

[0.官方Demo（脚本库+应用脚本）★](https://github.com/openLuat/Luat_2G_RDA_8955/tree/master/script)

[1.Lua-百度百科](https://baike.baidu.com/item/lua/7570719?fr=aladdin)

[2.Lua 教程|菜鸟教程](https://www.runoob.com/lua/lua-tutorial.html)

[3.Luat-Github](https://github.com/openLuat/Luat_2G_RDA_8955)

[4.Air800 GNSS+GPRS 模块](http://www.openluat.com/Product/gnssgprs/Air800.html)

[5.阿里云物联网平台 名词解释](https://help.aliyun.com/document_detail/30524.html?spm=a2c4g.11186623.2.25.3b861996k6z1xq&tdsourcetag=s_pcqq_aiomsg)

[6.阿里云-帮助文档](https://help.aliyun.com/?spm=5176.13279267.floorOne.dHelpDoc.6f44378eaQ9OPk&tdsourcetag=s_pcqq_aiomsg)

[7.物联网数据分析服务 > 数据开发 > 数据开发 > 使用示例](https://help.aliyun.com/document_detail/113689.html?spm=a2c4g.11186623.2.21.112c526aX7VJY0&tdsourcetag=s_pcqq_aiomsg)

[8.W5500如何通过 MQTT协议连接阿里云](https://w5500.com/code/W5500EVB/STM32+W5500_MQTT.html)
# 项目功能：
### 导游端：
1. 通过NFC或扫描二维码（当导游使用无NFC功能的手机时）添加游客到导游端地图中
2. 导游可在地图上查看所有已添加游客的位置以及旅游大巴的具体位置
3. 导游可自行设置危险（警示）区域，一旦有游客进入App立刻报警
4. app根据当前的游览景点范围自动划分游览区域（绿色线）一旦有游客外出则报警
5. 轻点某一个定位蓝色标记可查看该游客的信息及直接拨打其电话，另外可添加备注标记特殊旅客
6. 轻点大巴可联系大巴司机
7. app右下角显示当前游览景点及游览时间，方便导游掌握信息
### 游客端：
1. 含有印有二维码的NFC标签的吊牌，方便导游快速添加游客
2. 内置GPS可将本吊牌的位置实时上传至导游端
# 一、Air 800
### 1.引脚图
![管脚](https://img01.sogoucdn.com/app/a/100520146/9f2c7ed3ec8b72fc559b4ee65cfe9380)

# 二、项目实体

![](https://raw.githubusercontent.com/LengMingxuan/My-Image-Hosting-Service/master/img/3ds.png)

# 项目软件:

### 1.概念效果图：（阿里云可以直接导出KPI）
![IMG_6383.PNG](https://img03.sogoucdn.com/app/a/100520146/8a079493b27cc7ec6e62bb3ddaade8a6) 
