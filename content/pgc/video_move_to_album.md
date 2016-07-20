转移视频到某专辑接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/video/list/move-to-album

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
| channelid      | 视频id |必选    |
| series_id      | 专辑id |可选    |
返回示例
----------
<pre>
{
    "data": null,
    "err": 105004,
    "msg": "udpateUserChannel failure: series epg category deffrence: 71  "
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.9编辑视频信息
</pre>