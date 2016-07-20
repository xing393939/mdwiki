直播监控列表接口
----------

接口地址
----------
  * 正式接口：/userreview/report/live-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userchannelid       | 序号 |可选    |
| mode | 直播类型 camera:摄像头， xsplit:第三方软件，rtmp:已有直播流 |可选    |
| timelimit| 1:限时直播, 0:不间断直播  |可选    |
| livestatus| 直播状态 0:预约中, 1:正在直播, 2:直播完成 |可选    |
| channelid| 视频id |可选    |
| rtmpguid| rtmpguid|可选    |
| live2guid| live2guid |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "userChannelId": 106085,
            "screenShot": "http://live2image6.pplive.cn/liveplatform/156590586.jpg",
            "userId": 823,
            "userName": "450340497@qq.com",
            "userIp": "10.200.20.103",
            "userIsp": null,
            "mode": "camera",
            "timeLimit": 1,
            "liveStatus": 2,
            "liveStartTime": 1467273847067,
            "liveEndTime": 1467296351230,
            "realStartTime": null,
            "realEndTime": null,
            "channelId": 156590586,
            "channelName": "直播201606301548",
            "rtmpGuid": "2948b25ecd5c4c778c8e8eddd060f17f",
            "live2Guid": "934c422b4dbb432baca2f0388c964b51",
            "realStartTimeStr": "-----",
            "realEndTimeStr": "-----",
            "modeStr": "摄像头",
            "timeLimitStr": "限时直播",
            "liveStatusStr": "直播完成"
        }
    ],
    "msg": "success",
    "err": 0,
    "totalnum": 623
}
</pre>

返回结果说明
----------
<pre>
用到的java接口：
2.124	查询直播监控信息

"liveStatus": 直播状态，0:预约中,2:正在直播,2:直播完成
"mode": 直播类型，camera:摄像头，xsplit:第三方软件，rtmp:已有直播流
"modeStr": 直播类型
"timeLimitStr": 即时/24小时
"liveStatusStr": 直播状态
</pre>