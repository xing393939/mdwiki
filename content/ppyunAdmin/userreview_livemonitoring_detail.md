直播监控详情接口
----------

接口地址
----------
  * 正式接口：/userreview/livemonitoring/detail

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| channelwebid            | 视频id |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "channelId": "150123230",
            "channelName": "",
            "time": "1948-12-03 07:28",
            "channelWebId": "0a2dnqyXqaGioa2L4K2doac",
            "upStreamSpeed": 1235,
            "downViewCount": 239,
            "downLagCount": 10,
            "downLagRate": 0.42,
            "avgLagTime": 5.5
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
"time": 时间
"upStreamSpeed": 上行推流速度/kbps
"downViewCount": 下行观看人数
"downLagCount": 下行卡顿人数
"downLagRate": 下行卡顿率/%
"avgLagTime": 平均卡顿时间（s）
</pre>