直播监控列表接口
----------

接口地址
----------
  * 正式接口：/userreview/livemonitoring/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| channel_id            | 视频id |可选    |
| channel_name            | 视频名称 |可选    |
| user_name      | 用户名  |可选    |
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
            "id": 12,
            "categoryId": 222,
            "channelName": "name",
            "channelSummary": "summary",
            "coverImage": null,
            "fId": 333,
            "channelId": 12345,
            "channelType": 1,
            "createTime": 1403789110000,
            "channelWebId": "OUeqKJAPrib1Qzjac",
            "userName": "username@pptv.com",
            "transcodeStatus": 116,
            "liveStatus": "notstart",
            "duration": "300",
            "screenshot": "",
            "liveStartTime": "1948-12-03 07:28",
            "liveEndTime": "1948-12-26 10:48",
            "updateTime": 1403790230000,
            "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2Nq",
            "subUserName": "aaaa",
            "roomId": 12345455,
            "online": 522,
            "toIboReviewStatus": 0,
            "upStreamOutIPs": "117.135.159.4,118.123.3.120",
            "upStreamInIPs": "117.135.159.4,118.123.3.120"
        }
    ],
    "msg": "success",
    "err": 0,
    "totalnum": 38
}
</pre>

返回结果说明
----------
<pre>
...
</pre>