屏蔽或恢复视频接口
----------

接口地址
----------
  * 正式接口：http://admin.cloud.ppqa.com/public/index.php/api/ppcloud/allvideo/censor

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| channelid | 视频id |必选    |
| censored | 1是已屏蔽，0是正常 | 必选|
| reviewResult| 屏蔽原因 | 必选 |
返回示例
----------
<pre>
{
    "data": [],
    "msg": "success",
    "err": 0,
}
</pre>

返回结果说明
----------
<pre>

</pre>