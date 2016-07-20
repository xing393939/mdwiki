精彩节目管理列表接口
----------

接口地址
----------
  * 正式接口：/video/wonderful/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id      | 视频id |可选    |
| channelname            | 视频名称 |可选    |
| type      | type=1近一天，=2近三天  =3近一周  |可选    |
| startdate      | 开始时间，例20151026 |可选    |
| enddate      | 结束时间 |可选    |
| is_play | 状态，0下线 1上线 | 可选|
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": [
        {
            "id": 104681,
            "categoryId": 1056,
            "channelName": "hhhh",
            "channelSummary": "12",
            "coverImage": "",
            "fId": 67372,
            "isPlay": 1,
            "channelId": 156584523,
            "channelType": 2,
            "createTime": "2016-03-02 14:52:51",
            "channelWebId": "0a2dnqyaqKShm6mL4K2hoqrhoaCgn66W",
            "length": 0,
            "ppfeature": null,
            "userName": "jiahuixu@pptv.com",
            "transcodeStatus": 106,
            "liveStatus": "stopped",
            "duration": 689,
            "realDuration": 690,
            "screenshot": "/6c/3d/6c3d40d75d917a23ec9f4e0156584523/1.jpg",
            "liveStartTime": 1456901579023,
            "liveEndTime": 1456902279055,
            "updateTime": 1456903679000,
            "shareAuth": null,
            "nexttk": "0a2dnaubqaCdnq2WoKCcj-aipamg5aeVpKakmg",
            "subContactName": "",
            "vv": null,
            "isChild": 0,
            "nickName": null,
            "online": null,
            "sourceUserName": "aaaa",
            "timeLimit": 1,
            "timePreset": null,
            "sourceUser": 0,
            "epg_category_id": null,
            "info_status": null,
            "epgCategoryName": null,
            "seriesId": 0,
            "seriesName": null,
            "toibo": 0,
            "roomId": null,
            "reviewFailedReason": null,
            "displayable": 1,
            "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaahoaqaoqM%3D",
            "channelTypeStr": "直播",
            "siteName": "博客网",
            "isPlayStr": "上线",
        }
    ],
    "totalnum": 46
}
</pre>

返回结果说明
----------
<pre>
duration: 播放时长
</pre>