删除消息接口
----------

接口地址
----------
  * 新接口：http://api.pptvyun.com/pgc/api/message/list/delete

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName   | 用户名 |必选    |
| relationids | 消息id，多个用逗号隔开 |必选    |
返回示例
----------
<pre>
{
    "data": [],
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
...

用到pgc的接口：
5.64	更新商户端消息(删除/已读状态)
</pre>