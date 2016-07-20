点播监控列表接口
----------

接口地址
----------
  * 正式接口：/userreview/report/vod-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username| 用户名|可选    |
| fid | 文件fid |可选    |
| channelname|视频名称 |可选    |
| transcodestatus| 状态 0:文件创建, 99:重传中, 101:待压制, 102:压制中, 106:待审核, 107:审核中, 111:待分发, 112:分发中, 180:审核不通过, 190:分发失败, 150:压制失败, 200:可播放 |可选    |
| channeltype| 点播类型  1点播，2直转点 |可选    |
| channelid| 视频id|可选    |
| md5| 视频md5|可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "userChannelId": 111,
            "screenShot": 111,
            "userName": 111,
            "userId": 111,
            "fid": 111,
            "channelName": 111,
            "duration": 111,
            "transcodeStatus": 111,
            "channelType": 1,
            "channelId": 111,
            "md5List": [
                {
                    "md5Type": 1,
                    "md5": "777774ceb63c40c9bd9f2671237c6fb9"
                }
            ],
            "detail": "aa",
            "transcodeStatusStr": "待分发",
            "channelTypeStr": "点播",
            "md5ListStr": "流畅: 777774ceb63c40c9bd9f2671237c6fb9\n"
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
2.128	查询点播监控信息

"duration": 时长
"detail": 详情
"transcodeStatusStr": 压制状态
"channelTypeStr": 视频类型：直播/点播/直转点
"md5ListStr": 成片MD5
</pre>