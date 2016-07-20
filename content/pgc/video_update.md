编辑视频接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/video/list/update

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
| channelid      | 视频id |必选    |
| series_id      | 专辑id |可选    |
| epg_category_id      | epg分类id |可选    |
| channelname      | 视频名 |可选    |
| channelsummary     | 视频描述 |可选    |
返回示例
----------
<pre>
{
    "data": {
        "id": 39035,
        "categoryId": null,
        "userId": 497,
        "channelName": "PostmenInTheMountains101",
        "channelSummary": "测试上传视频增加专辑选择",
        "coverImage": null,
        "fId": null,
        "isPlay": null,
        "channelId": null,
        "channelType": null,
        "createTime": null,
        "channelWebId": null,
        "length": null,
        "ppfeature": null,
        "userName": null,
        "transcodeStatus": null,
        "liveStatus": null,
        "duration": null,
        "screenshot": null,
        "liveStartTime": null,
        "liveEndTime": null,
        "updateTime": null,
        "isDeleted": null,
        "shareAuth": null,
        "nexttk": null,
        "subContactName": null,
        "passportName": null,
        "vv": null,
        "isChild": null,
        "nickName": null,
        "liveStatusLong": null,
        "online": null,
        "sourceUserName": null,
        "watchProtocol": null,
        "timeLimit": null,
        "sourceUser": null,
        "epg_category_id": null,
        "info_status": null,
        "epgCategoryName": null,
        "seriesId": null,
        "roomId": null,
        "reviewFailedReason": null,
        "pptvsPlayStr": null
    },
    "err": 0,
    "msg": "udpateUserChannel success"
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.9编辑视频信息
</pre>