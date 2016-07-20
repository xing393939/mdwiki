用户基本资料接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/account/list/user-info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
返回示例
----------
<pre>
{
    "data": {
        "id": 86,
        "userId": 497,
        "type": 0,
        "name": "晨晨",
        "phone": null,
        "mobile": "13774423374",
        "contactName": null,
        "site": null,
        "address": null,
        "email": "123456@163.COM",
        "qq": null,
        "idCode": "310108198601012781",
        "orgCode": null,
        "pic1": "http://svc.pptvyun.com/svc/pic/0a2cj-aioaSgnq-YqaafmauXqOzU3erVqp-b0OjU09Xe4qTV4OTil9nU3Z_Y2d_In6GloKWepaibm6vIn6mfmqeco9WgotnK1KWhntrK06KgyqfL1qTOoNjLoaail-DV1w.jpg",
        "pic2": "http://svc.pptvyun.com/svc/pic/0a2cj-aioaSgnq-YqaafmauXqOzU3erVqp-b0OjU09Xe4qTV4OTil9nU3Z_Y2d_In6nPoaWZptKbzdnHn6GdzqnL06Glntyap6WendzKptPPn6adodOkzdnLqdGll-DV1w.jpg",
        "pic3": null,
        "pic4": null,
        "pic5": null,
        "status": 200,
        "applyReason": null,
        "createTime": 1435646859000,
        "userName": "wengjiawei9",
        "cardStatus": null,
        "isWithdraw": 1
    },
    "err": 0,
    "msg": "getPgcUserInfo success"
}
</pre>

返回结果说明
----------
<pre>
"userName": 用户名
"type": 类型，0个人，1公司
"name": 真实姓名
"mobile": 手机
"email": 邮箱
"qq": QQ
"idCode": 身份证号
"pic1": 图片1
"pic2": 图片2
"pic3": 图片3,
"pic4": 图片4,
"pic5": 图片5,

用到pgc的接口：
5.5获取用户基本资料
</pre>