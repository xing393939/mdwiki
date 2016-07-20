视频详情接口
----------

接口地址
----------
  * 正式接口：http://172.16.0.105/pptv3/public/index.php/api/ppcloud/video/info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id      | 视频id |可选    |
返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": {
        "id": 104696,
        "categoryId": 647,
        "userId": 203,
        "channelName": "金华测试2",
        "channelSummary": "阿萨法萨芬",
        "coverImage": "",
        "fId": 67522,
        "isPlay": 1,
        "channelId": 156584892,
        "channelType": 2,
        "createTime": "2016-03-03 15:17:56",
        "channelWebId": "0a2dnqyaqKSkoqiL4K2emanhoaCgn6-b",
        "length": 0,
        "ppfeature": null,
        "userName": "meizhang@pptv.com",
        "transcodeStatus": 107,
        "liveStatus": "stopped",
        "duration": 279,
        "realDuration": 279,
        "screenshot": "/cf/0b/cf0bfaea70aadffce08089e156584892/1.jpg",
        "liveStartTime": 1456989488255,
        "liveEndTime": 1456989773448,
        "updateTime": "2016-03-09 14:26:41",
        "isDeleted": 0,
        "shareAuth": 0,
        "nexttk": null,
        "subContactName": null,
        "passportName": null,
        "vv": null,
        "isChild": null,
        "nickName": null,
        "liveStatusLong": 2914494002437,
        "online": null,
        "sourceUserName": null,
        "watchProtocol": "all",
        "timeLimit": 1,
        "timePreset": null,
        "sourceUser": 0,
        "epg_category_id": null,
        "info_status": null,
        "epgCategoryName": null,
        "seriesId": 0,
        "seriesName": null,
        "toibo": null,
        "roomId": null,
        "reviewFailedReason": null,
        "toIbo": 0,
        "toPptv": 1,
        "epgCateName": null,
        "displayable": 1,
        "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaahoaqdqaI%3D",
        "categoryStr": "综艺 >> 其他综艺",
        "openingEndTime": "00:00:00",
        "endStartTime": "00:00:00",
        "playingUrl": "http://172.17.1.15:80/prod/cf/0b/fa/3d99566553a9a471bd560324ebd2371b.mp4",
        "channelTypeStr": "直播",
        "tagStr": "科教频道"
    }
}
</pre>

返回结果说明
----------
<pre>
duration: 播放时长
</pre>