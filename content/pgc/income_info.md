提现前账号收益信息接口（get请求）
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/profit/list/income-info

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
        "amount": 330,
        "cardName": "陈成",
        "cardNo": "622501234567890",
        "withdraw_auth": 1
    },
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
withdraw_auth：1可以提现，0不能提现

用到的pgc接口：
5.23获取账户信息
</pre>