删除视频接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/video/list/delete

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName   | 用户名 |必选    |
| ids        | 视频主键id, 以逗号分隔 (注意是主键id,不是channelid) |必选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "id": 39035,
            "err": 0
        }
    ],
    "err": 0,
    "msg": "deleteUserChannel success"
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.16视频删除接口
</pre>