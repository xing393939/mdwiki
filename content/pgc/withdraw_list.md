提现日志列表接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/withdraw/list/index

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
| status      | 0待提现 200已提现 100已驳回，多个用逗号隔开，默认0 |可选    |
| startdate      | 开始时间，例20151026 |可选    |
| enddate      | 结束时间 |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "createTime": "2015-05-15",
            "amount": 200,
            "statusStr": "待提现"
        }
    ],
    "err": 0,
    "msg": "success",
    "totalnum": 12
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.21待支付列表/提现日志列表
</pre>