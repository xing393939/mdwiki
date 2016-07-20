直播vms详情接口
----------

接口地址
----------
  * 正式接口：/userreview/report/live-vms-info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| channelid      | 视频id |可选    |
返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": {
        "channelId": 158434633,
        "pushStreamStatus": "ok",
        "pullStreamStatus": "error",
        "cutterReadStatus": "ok",
        "cutterTransStatus": "ok",
        "vmsStreamStatus": "ok",
        "pushTime": 1465379213679,
        "channelFormat": "h264",
        "channelResolution": "640*480",
        "channelRate": 500,
        "channelFrameRate": 25,
        "audioFormat": "acc",
        "audioSampleRate": 444100,
        "audioRate": 100,
        "cutterIp": 100,
        "dcIp": 100,
        "rtmpgateIp": 100,
        "vmsServerIp": 100,
        "publishUrl": "rtmp://xxx"
    }
}
</pre>

返回结果说明
----------
<pre>
2.125	查询直播监控VMS信息

"pushStreamStatus": //DC推流状态(针对推流方式)
"pullStreamStatus": //rtmpgate拉流状态(针对已有直播流方式)
"cutterReadStatus": //cutter读流状态
"cutterTransStatus": //cutter切流状态
"vmsStreamStatus": //pms推流状态(根据上行速率判断)
"pushTime": //推流时间
"channelFormat": //视频格式 h264
"channelResolution": //分辨率
"channelRate": //视频码率
"channelFrameRate": //视频帧率
"audioFormat": //音频格式 aac
"audioSampleRate": //音频采样率 44100
"audioRate": //音频码率
"cutterIp": //cutter服务器IP
"dcIp": //DC IP
"rtmpgateIp": //拉流服务器IP
"vmsServerIp": //推流时边缘服务器IP
"publishUrl": //推流地址或第三方流地址
</pre>