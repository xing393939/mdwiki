用户银行卡账户信息接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/account/list/card-info

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
        "id": 186,
        "userId": 497,
        "bankName": "上海",
        "subBranch": "上海",
        "city": "上海",
        "name": "上海",
        "cardNo": "1234567890",
        "status": 200,
        "isDeleted": 0,
        "reason": null,
        "ip": null,
        "userName": null,
        "phone": null,
        "mobile": null,
        "rate": null,
        "createTime": 1444877372000,
        "updateTime": 1444877372000,
        "userInfoName": null
    },
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
"status": 0是未审核 200是审核通过
"bankName": 开户银行
"subBranch": 支行名称
"city": 城市
"name": 户名
"cardNo": 银行卡号

用到pgc的接口
5.18获取用户卡号
</pre>