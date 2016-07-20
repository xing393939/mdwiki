未读消息数接口
----------

接口地址
----------
  * 新接口：http://api.pptvyun.com/pgc/api/message/list/unread

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName   | 用户名 |必选    |
返回示例
----------
<pre>
{
    "data": {
        "totalUnread": 3,
        "atMeUnread": 2,
        "systemUnread": 1
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
5.67	查询消息件数
</pre>