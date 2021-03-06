## 期末项目产品需求文档

| 发布日期 | 2019.12.2    |
| -------- | ------------ |
| 产品名称 | 爱车保险 |
| 文档状态 | 进行中       |
| 文件主人 | 何俊鹏       |
| 设计者   | 何俊鹏       |
| 开发者   | 何俊鹏       |
| 测试者   | 何俊鹏       |

### 多版本价值主张

##### 一句话版本

+ 爱车保险，让您线上解决全套的汽车保险服务。

##### 一分钟版本

+ 目前，调用百度车辆外观损伤识别API，爱车保险可以做到针对车辆外观损伤位置，类别，和零部件识别，在汽车保险行业内，可以为保险公司做到初步的汽车损伤识别，辅助人工理赔，从而提高人工理赔的效率和准确性。在这个基础之上，可以为保险公司节省人力资源的消耗，同时也提高了理赔的精确度，减少了保险公司的错误理赔消耗。

#### 20X20PPT版本

#### [20X20PPT](https://github.com/wangyangmin/final_project_api/blob/master/API_%E7%88%B1%E8%BD%A6%E4%BF%9D%E9%99%A9.pptx)

### (一)加值宣言：

+ 爱车保险APP，在充分理解了用户对自己爱车遭受的损伤程度了解的需求以及汽车保险公司在业务量扩张的背景下需要改革业务以求的竞争中实现提升。

+ 假定用户在遭遇交通事故之后要要申请保险理赔，用户拍摄车辆受损的照片上传到爱车保险APP申请理赔，爱车保险APP调用车辆外观损伤识别API，车辆外观损伤识别API目前可以识别32种汽车外观零部件，五大类外观识别。在初步的车辆外观损伤识别后给予车辆受伤类型、受伤等级定位，根据定位配送订单给擅长此类理赔的工作人员处理，以求提高保险理赔的准确度和效率。

+ 在智能定损之后，系统定位用户的所在地，可以向推荐，引导用户到周边的4S汽修店进行汽车维修。

+ 用户通过拍摄，上传车辆受损照片在系统中获取自己车辆的受损程度以及保险公司的理赔方案。

### （二）核心价值：（最小可行性产品）

+ 目前百度的车辆外观损伤识别API可以通过机器图形学里的图片识别可以做到智能的辆受伤类型、受伤等级定位，为保险公司提高理赔效率、提高理赔的精确度，从而提高公司的效益。

+ 可以为普通用户提供线上的保险理赔服务，让理赔的过程清晰可见。

### （三）背景：

+ 2019年6月中国交管局数据显示，目前中国汽车保有量已经达到了2.5亿量，2018年的数据显示，中国车险行业保费已经达到了7834亿元。目前中国汽车保险业正在飞速的发展着，如何抢占这个巨大的市场蛋糕需要保险公司创新，而爱车保险这个APP就能够很好的适应汽车保险行业所需要的创新。

+ 在中国互联网迅速发展的背景下，中国也有庞大的网民群体，在网民群体之中，适应了APP操作的也占据绝大多数，所以爱车APP可以也符合中国消费者的习惯。

### （四）目的：

+ 创新，让你行车更有安全感，爱车保险，是你勇敢行车的后盾。

### （五）目标：

+ 前期目标：

1.通过车辆外观识别API的调用，为用户和保险公司对汽车受损类型和汽车受损程度定位。

+ 后期目标：（目前不做）

1.在实现前期目标的前提下，积累训练集数据，后期可以借助大量的数据集进行机器学习，后期可以对车辆受损程度级别小的理赔申请进行自动的定损、审核和理赔。

### （六）用户：

+ 汽车业务保险公司

+ 普通的汽车用户

### （七）用户痛点：

保险公司：

+ 人工理赔需要耗费巨大的人力资源，而且现在业务量还在不断地增加，对人力资源地需求会不断的增加，除非有新的解决方案。

+ 人工理赔也有着不准确性，人们在情绪和能力的制约下，有可能造成理赔的出错，从而增加了公司的财务支出或者是造成用户的不满。

普通用户：

+ 传统的理赔方式会消耗比较多的时间，同时业务人员的回复也比较的慢，心急自己的爱车的用户也不知该如何是好。

+ 用户想知道自己的理赔过程以及进度，这一些用户都想有数据可查。

### （八）用户需求:（使用的人工智能要反映到需求列表中）

| 用户案例         | 对应功能    | 重要性 |
| ---------------- | ----------- | ------ |
| 汽车外观损伤识别 | 受损识别API | 重要   |
| 资质维修点导航   | 路线导航    | 重要   |
| 用户了解理赔进程 | 数据更新    | 一般   |


### （九）使用者交互与设计（axure产品原型）

#### 登陆界面

![登陆](https://images.gitee.com/uploads/images/2020/0103/182356_9eacee53_1829884.png)


#### 首页示意图

![首页示意图](https://images.gitee.com/uploads/images/2020/0103/182355_82915675_1829884.png)


#### 照片审核

![照片审核](https://images.gitee.com/uploads/images/2020/0103/182355_e261de68_1829884.png)


#### 受损等级评定

![受损等级](https://images.gitee.com/uploads/images/2020/0103/182356_06a7a86f_1829884.png)


#### 理赔进度

![理赔进度](https://images.gitee.com/uploads/images/2020/0103/182356_878d6c17_1829884.png)


#### 维修地点推荐

![维修地点推荐](https://images.gitee.com/uploads/images/2020/0103/182356_6fb1f2a5_1829884.png)

#### 维修地点详情

![维修点详情](https://images.gitee.com/uploads/images/2020/0103/182356_af8ff496_1829884.png)


#### 维修地点导航

![维修点导航](https://images.gitee.com/uploads/images/2020/0103/182356_37b5ff00_1829884.png)


#### 消息页面

![消息页面](https://images.gitee.com/uploads/images/2020/0103/182355_f1e44c4c_1829884.png)

#### 保险推荐

![保险推荐](https://images.gitee.com/uploads/images/2020/0103/182356_80448a03_1829884.png)


#### 我的信息

![我的信息](https://images.gitee.com/uploads/images/2020/0103/182356_3dd33709_1829884.png)


#### 我的资料

![我的资料](https://images.gitee.com/uploads/images/2020/0103/182356_baeea549_1829884.png)


#### 我的爱车

![我的爱车](https://images.gitee.com/uploads/images/2020/0103/182356_2260ed1d_1829884.png)


### （十）产品结构图

![原型框架图](https://images.gitee.com/uploads/images/2020/0103/182355_95f3c1db_1829884.png)


### （十一）API的运用：

#### 百度车辆外观受损识别API

+ 车辆外观损伤识别API：为车辆损伤类型和严重程度定位。

+ 智能导航API：为用户提供附近的汽车维修点进行汽车的检查和维修。

接口地址：https://aip.baidubce.com/rest/2.0/image-classify/v1/vehicle_damage

请求方式：https://aip.baidubce.com/oauth/2.0/token

输入：

代码模块导入：

```
import base64
import urllib
from typing import BinaryIO
from urllib.parse import urlencode
from urllib import request
import requests
from urllib.request import urlopen
import json
```

输入代码：

```
host = 'https://aip.baidubce.com/oauth/2.0/token?grant_type=client_credentials&client_id=GjE4Yiu9IdPdq5LYrm7vPG2w&client_secret=2GcjHthph7vxwXzfxGU409G6mOp8wKkj'
headers = {
    'Content-Type': 'application/x-www-form-urlencoded'
}
res = requests.get(url=host, headers=headers).json()
access_token=res['access_token']

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/vehicle_damage"

f = open('2.jpg', 'rb')
img = base64.b64encode(f.read())
params = {"image":img}
request_url = request_url + "?access_token=" + access_token
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```


结果输出

```
{'log_id': 3412726100092736631, 'result': {'damage_info': [{'parts': '右后门', 'type': '褶皱或波浪', 'probability': 83}]}}
```

百度车辆外观损伤识别API测试：

1.在测试中我输入了图片1

![车辆1](https://images.gitee.com/uploads/images/2020/0103/182355_5df54c64_1829884.jpeg)


```
{'log_id': 3412726100092736631, 'result': {'damage_info': [{'parts': '右后门', 'type': '褶皱或波浪', 'probability': 83}]}}
```

百度车辆外观损伤识别API准确的识别了车辆损伤的位置，和损伤的类别，损伤程度。

2.测试中，我输入了图片2

![车辆2](https://images.gitee.com/uploads/images/2020/0103/182355_95138ad4_1829884.jpeg)


```
{'log_id': 7635812925649155255, 'result': {'damage_info': [{'numeric_info': [{'width': 0.21999999880791, 'area': 0.80210000276566, 'ratio': 0.0079494547098875, 'height': 6.0100002288818}, {'width': 0.11999999731779, 'area': 0.12720000743866, 'ratio': 0.0012606541858986, 'height': 1.5599999427795}], 'parts': '后保险杠', 'type': '刮擦', 'probability': 78}]}}
```

百度车辆外观损伤识别API依旧能够稳定的识别汽车受损的位置和受损类型。

#### 百度导航API

```
import json
from urllib.request import urlopen
import urllib
```
```
s1="42.909089"
s2="116.382668"
t1="31.194255"
t2="121.334198"
a1=r"http://api.map.baidu.com/routematrix/v2/driving?output=json"
a2=r"&origins="+s1+","+s2
a3=r"&destinations="+t1+","+t2
a4=r"&coord_type=wgs84"
a5=r"&tactics=11"
a6=r"&ak=abcdefghijklmnopqrstxyz"
```
```
b = urlopen(http://api.map.baidu.com/geocoder?address=北京市海淀区上地信息路9号奎科科技大厦&output=html&src=webapp.baidu.openAPIdemo)
c=b.read() 
result = json.loads(c)
```
```
print(c["status"])
print(c["result"][0]["distance"]["value"]/1000)
print(c["result"][0]["duration"]["value"]/60)
```
```
{'status': 0, 'result': 
[{'distance': {'text': '1723.8公里', 'value': 1723771},
 'duration': {'text': '19.5小时', 'value': 70279}}],
 'message': '成功'}
```
经过测试，百度地图导航API能够计算出两地之间的距离，同时还能计算车程。最后计算出路线。

#### 阿里云图片识别

```
import urllib.request
import urllib.parse
import json
import time
import base64
```
```
image_path = '1.jpg'
with open(image_path, 'rb') as f: 
    data = f.read()
    encodestr = str(base64.b64encode(data),'utf-8')
headers = {
         'Authorization': 'APPCODE 3F2504E04F8911D39A0C0305E82C3301', 
         'Content-Type': 'application/json; charset=UTF-8'
    }
```
```
def posturl(url,data={}):
    try:
        params=json.dumps(dict).encode(encoding='UTF8')
        req = urllib.request.Request(url, params, headers)
        r = urllib.request.urlopen(req)
        html =r.read()
        r.close();
        return html.decode("utf8")
    except urllib.error.HTTPError as e:
        print(e.code)
        print(e.read().decode("utf8"))
    time.sleep(1)
```
```
if __name__=="__main__":
    url_request="https://ocrapi-advanced.taobao.com/ocrservice/advanced"   
    dict = {'img': encodestr}
    html = posturl(url_request, data=dict)
    print(html,type(html))  
    jos = json.loads(html)    
    print(jos,type(jos))
    result = jos['content'] 
    print('识别的结果：',result)
```
![1.jpg](https://images.gitee.com/uploads/images/2020/0103/182355_83c64ce3_1829884.jpeg)

![测试结果](https://images.gitee.com/uploads/images/2020/0103/182355_e6d5c553_1829884.png)

同样用这张图片在阿里云图像识别测试，测试的结果出来的是数字，数字对应相应物品，但是测试的结果却不准确。

总结：目前市面上，针对车辆外观受损识别的API只有百度一家，其他平台虽然有关于图像识别类型的API，但是在汽车受损识别领域都远不如百度API成熟，稳定，目前百度是这个领域的领先者。

### （十二）AI产品概率性：

+ 目前，车辆外观损伤识别API针对常见小汽车车型，识别车辆外观受损部件及损伤类型，可识别数十种车辆部件、五大类外观损伤（刮擦、凹陷、开裂、褶皱、穿孔）。已经可以的完成车辆的外观受损识别，同时还能够具体到零部件受损情况。


+ 单一的车辆受损类型，使用百度车辆外观受损API可以快速的识别出来，但是综合多样的车辆受损情况，API运行的不出结果。

解决方法：逐部分的上传车辆受损的照片、


+ 百度车辆外观受损识别API对上传的车辆受损图片的要求比较高，需要较高清的图片，同时图片中的车辆还需要比较干净，否则影响准确的识别。

解决方法：擦拭车外的脏物、对准车辆的受损位置拍照提升拍照的精确度。

### (十三)API使用风险评估

#### 产品的可行性:

+ 爱车保险是小程序，本身的所需要的内存不大，小程序的使用简易迎合了用户快速理赔的心理。

+ 依据目前的汽车保险业务增长，爱车保险小程序有了群众的基础，同时在保险公司的需求也是明显的，可以与保险公司商谈合作，以求进一步的发展，实现共赢。

+ 爱车保险是小程序开发，开发量也比较小，利用现有的API也能大量的节约开发资源，将大大减少成本。

#### 交互需求：

+ 申请拍照功能需要获得手机的授权

+ 点击搜索或者其他需要输入的时候，需要弹出输入键盘，同时在点击搜索键时或空白位置的时候，键盘会退出。

+ 在首页中的功能模块中，点击可以跳转到其功能的位置上。

+ 搜索框默认为空

#### 异常流：

+ 根据API返回的数字段，在小程序中转换得出具体的输出结果，根据返回的错误结果我们可以让用户根据结果重新上传图片或者重新拍摄光线良好的照片。

+ 车辆损伤输出结果与用户判断不一的时候，提示用户详细拍下汽车损伤位置细节的照片。

+ 用户不满维修点推荐的话，可以选择有维修资格和合作的维修点实现汽车维修。

#### 非功能性需求：

+ 可用性：百度车辆外观损伤识别API有1000次的免费调用，同时也处在免费使用的期间，在这个期间可以免费的调用API。

+ 性能：预计小程序上线，在未实现与保险公司合作的前期，使用人数日均5000人次，因而对于网络宽带的要求不高，100M宽带可以实现用户使用需求。

+ 易用性：目前小程序的原型界面简洁，符合用户使用习惯。

+ 安全性：小程序使用微信登陆，微信的安全性值得信赖。

#### 结果预期：

+ 前期：前期处于市场测试期，产品先投入市场，得出测试数据和积累用户。

+ 中期：寻求与保险公司的合作，实现小程序的脱离，正式开发APP，正式投入市场运营。

+ 日常运营，保持用户增长，不断优化APP，将APP做大做强，实现公司化运营。

#### 清单

[原型图仓库](http://nfunw019.gitee.io/car_insurance_prototype/#g=1&p=%E7%88%B1%E8%BD%A6%E4%BF%9D%E9%99%A9%E7%99%BB%E9%99%86 "原型图")
