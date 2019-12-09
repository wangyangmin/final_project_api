## 期末项目产品需求文档

| 发布日期 | 2019.12.2    |
| -------- | ------------ |
| 产品名称 | 爱车保险 |
| 文档状态 | 进行中       |
| 文件主人 | 何俊鹏       |
| 设计者   | 何俊鹏       |
| 开发者   | 何俊鹏       |
| 测试者   | 何俊鹏       |

### （一）加值宣言：

爱车保险APP，在充分理解了用户对自己爱车遭受的损伤程度了解的需求以及汽车保险公司在业务量扩张的背景下需要改革业务以求的竞争中实现提升。

假定用户在遭遇交通事故之后要要申请保险理赔，用户拍摄车辆受损的照片上传到爱车保险APP申请理赔，爱车保险APP调用车辆外观损伤识别API，车辆外观损伤识别API目前可以识别32种汽车外观零部件，五大类外观识别。在初步的车辆外观损伤识别后给予车辆受伤类型、受伤等级定位，根据定位配送订单给擅长此类理赔的工作人员处理，以求提高保险理赔的准确度和效率。

在智能定损之后，系统定位用户的所在地，可以向推荐，引导用户到周边的4S汽修店进行汽车维修。

用户通过拍摄，上传车辆受损照片在系统中获取自己车辆的受损程度以及保险公司的理赔方案。

### （二）核心价值：（最小可行性产品）

目前百度的车辆外观损伤识别API可以通过机器图形学里的图片识别可以做到智能的辆受伤类型、受伤等级定位，为保险公司提高理赔效率、提高理赔的精确度，从而提高公司的效益。

可以为普通用户提供线上的保险理赔服务，让理赔的过程清晰可见。

### （三）背景：

2019年6月中国交管局数据显示，目前中国汽车保有量已经达到了2.5亿量，2018年的数据显示，中国车险行业保费已经达到了7834亿元。目前中国汽车保险业正在飞速的发展着，如何抢占这个巨大的市场蛋糕需要保险公司创新，而爱车保险这个APP就能够很好的适应汽车保险行业所需要的创新。

在中国互联网迅速发展的背景下，中国也有庞大的网民群体，在网民群体之中，适应了APP操作的也占据绝大多数，所以爱车APP可以也符合中国消费者的习惯。

### （四）目的：

创新，让你行车更有安全感，爱车保险，是你勇敢行车的后盾。

### （五）目标：

前期目标：

1.通过车辆外观识别API的调用，为用户和保险公司对汽车受损类型和汽车受损程度定位。

后期目标：（目前不做）

1.在实现前期目标的前提下，积累训练集数据，后期可以借助大量的数据集进行机器学习，后期可以对车辆受损程度级别小的理赔申请进行自动的定损、审核和理赔。

### （六）用户：

1.汽车业务保险公司

2.普通的汽车用户

### （七）用户痛点：

保险公司：

1.人工理赔需要耗费巨大的人力资源，而且现在业务量还在不断地增加，对人力资源地需求会不断的增加，除非有新的解决方案。

2.人工理赔也有着不准确性，人们在情绪和能力的制约下，有可能造成理赔的出错，从而增加了公司的财务支出或者是造成用户的不满。

普通用户：

1.传统的理赔方式会消耗比较多的时间，同时业务人员的回复也比较的慢，心急自己的爱车的用户也不知该如何是好。

2.用户想知道自己的理赔过程以及进度，这一些用户都想有数据可查。

### （八）用户需求:（使用的人工智能要反映到需求列表中）

### （九）使用者交互与设计（axure产品原型）

### （十）产品结构图

### （十一）API的运用：

1.车辆外观损伤识别API：为车辆损伤类型和严重程度定位。

2.智能导航API：为用户提供附近的汽车维修点进行汽车的检查和维修。

### （十二）AI产品概率性：

### (十三)API使用风险评估

产品的可行性:

交互需求：

异常流：

非功能性需求：

结果预期：

清单

