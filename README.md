#### 1. 业务面

##### 1.1 抖店

###### 1.1.1 订单信息

感知下单之后的动作：

a. 若可以对接系统，则由抖店通知我们的系统，需要以下条件
<img width="631" alt="image" src="https://github.com/felogh/douShopRemote/assets/12730185/013654ec-8aa8-44e8-809b-bfeeddead773">


b. 若无法对接，则使用定时任务定期扫描请求订单变化，接口可用如下

订单列表查询https://op.jinritemai.com/docs/api-docs/15/1342

订单详情查询https://op.jinritemai.com/docs/api-docs/15/1343



###### 1.1.2 获取明文手机信息

批量解密接口https://op.jinritemai.com/docs/api-docs/15/982

看接口描述详情，虚拟号等限制，若为虚拟号，则调用如下接口报备

明文手机号报备接口https://op.jinritemai.com/docs/api-docs/15/1550



##### 1.2  企业微信获客链接生成

创建获客链接https://developer.work.weixin.qq.com/document/path/97394

获取由获客链接添加的客户信息https://developer.work.weixin.qq.com/document/path/97395

##### 1.3 发送短信

示例代码https://cloud.tencent.com/document/product/382/43194#.E7.A4.BA.E4.BE.8B.E4.BB.A3.E7.A0.81.5B.5D(id.3Aexample)

签名+模版问题需要走公司流程（经营执照之类的）

<img width="1506" alt="image" src="https://github.com/felogh/douShopRemote/assets/12730185/65270aba-e625-4ec7-a486-d2655aab1836">


目前自测用的公众号



#### 2. 管理面

##### 2.1 客户管理

企业可通过此接口获取成员联系客户的数据，包括发起申请数、新增客户数、聊天数、发送消息数和删除/拉黑成员的客户数等指标。

https://developer.work.weixin.qq.com/document/path/92275



获取客户详情

https://developer.work.weixin.qq.com/document/path/92265



获客助手组件

https://developer.work.weixin.qq.com/document/path/99482



##### 2.2 订单管理

看后续安排，有数据
