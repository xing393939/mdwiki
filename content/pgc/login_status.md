获取用户是否登录接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/account/list/login-status

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey，可以传空 |必选|
| userName   | 用户名，可以传空 |必选    |
返回示例
----------
<pre>
{
    "data": {
        "username": "wengjiawei9"
    },
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
...

用到pgc的接口：
无
</pre>