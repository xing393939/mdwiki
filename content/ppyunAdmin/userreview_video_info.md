获取单个视频信息接口
----------

接口地址
----------
  * 正式接口：/video/video/info

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
        "id": 105950,
        "categoryId": 804,
        "userId": 542,
        "channelName": "111",
        "channelSummary": "aaa",
        "coverImage": "http://grocery.pptv.com/lpic/687/afe/490/350f95d07bc137ff641e53c60fbfdeb2.png",
        "fId": 71462,
        "isPlay": 1,
        "channelId": 156589985,
        "channelType": 1,
        "createTime": 1465807784000,
        "channelWebId": "0a2dnqyaqKmloauL4K2hnajhoaChoquV",
        "length": 23952862,
        "ppfeature": null,
        "userName": "scdddk@163.com",
        "transcodeStatus": 200,
        "liveStatus": "stopped",
        "duration": 216,
        "realDuration": 216,
        "screenshot": "http://grocery.pptv.com/lpic/296/cba/706/29cd9f10e0f41e5126d81f26e7138558.jpg",
        "liveStartTime": 1465807924480,
        "liveEndTime": 1465808201795,
        "updateTime": 1466128751000,
        "isDeleted": 0,
        "shareAuth": 0,
        "nexttk": null,
        "subContactName": null,
        "passportName": null,
        "vv": null,
        "isChild": null,
        "nickName": null,
        "liveStatusLong": 2931936535405,
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
        "toibo": 0,
        "live2vodStatus": 14,
        "toIboReviewStatus": 200,
        "toIboReviewOperator": null,
        "roomId": null,
        "reviewFailedReason": null,
        "siteName": "b",
        "toIbo": 0,
        "toPptv": 0,
        "epgCateName": null,
        "displayable": 0,
        "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaahoa%2BeqKU%3D",
        "msgflash": "http://player.pptvyun.ppqa.com/svc/flashplayer/pl/0a2dnqyaqKmloauL4K2hnajhoaChoquV.swf"
    }
}
</pre>

返回结果说明
----------
<pre>
用到的java接口：
2.26	获取视频信息

msgflash: 播放swf地址
</pre>