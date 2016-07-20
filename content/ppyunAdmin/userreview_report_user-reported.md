用户上报列表接口
----------

接口地址
----------
  * 正式接口：/userreview/report/user-report-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username       | 用户名，可模糊搜索 |可选    |
| reportip   | 用户ip |可选    |
| channeltype      | 视频类型，1点播，2直播  |可选    |
| failuretype | 故障现象 |可选    |
| channelid | 视频id |可选    |
| edgeip| 服务器ip|可选    |
| cutter_ip| cutter ip | 可选 |
| status| 处理状态  0未处理，1处理中，2处理完成 |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "reportId": 11111,
            "createTime": "2015-11-09 15:30:46",
            "failureTime": "2015-11-09 15:30:46",
            "userName": "张三",
            "userId": 101,
            "reportIp": "111.111.111.111",
            "reportIsp": "上海电信",
            "failureTypeId": 1,
            "failureType": "观看黑屏",
            "failureContent": "xxx",
            "channelType": 1,
            "channelId": 15500011,
            "streamUrl": "rtmp://60.55.12xx547c558f7",
            "playServerUrl": "rtmp://60.55.1xx34159ef",
            "edgeIp": "60.55.12.812",
            "upstreamRate": 500,
            "contactType": 0,
            "contact": "133xxx",
            "status": 1,
            "reason": "停电了",
            "channelTypeStr": "点播",
            "statusStr": "处理中",
            "contactTypeStr": "其他"
        }
    ],
    "msg": "success",
    "err": 0,
    "totalnum": 1
}
</pre>

返回结果说明
----------
<pre>
用到的java接口
2.120	查询用户上报

"reportId": 自增id
"createTime": 提交时间
"failureTime": 故障发生时间
"reportIp": 用户ip
"reportIsp": 用户运营商
"failureType": 故障类型
"failureContent": 故障描述
"channelType": 视频类型，1点播，2直播
"streamUrl": 直播流地址
"playServerUrl": 播放地址(只针对直播主播端，一般会有两条记录，通常使用第一条)
"edgeIp": 播放服务器ip(同播放地址)
"upstreamRate": 上行速率(直播创建端)
"contact": 联系方式内容
"reason": 故障原因
"channelTypeStr": 视频类型
"statusStr": 处理状态：未处理/处理中/处理完成
"contactTypeStr": 联系方式
</pre>