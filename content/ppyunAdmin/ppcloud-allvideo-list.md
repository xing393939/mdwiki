全平台视频列表接口
----------

接口地址
----------
  * 正式接口：http://admin.cloud.ppqa.com/public/index.php/api/ppcloud/allvideo/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username       | 用户名，可模糊搜索 |可选    |
| channelid | 视频id |可选    |
| orderby   | vv，flow，createtime |可选    |
| isillegal | =1搜索犯规的视频 |可选    |
| rangetype      | =1前一天，=2前一个星期，=3前一月  |可选    |
| startdate      | 开始时间，例20151026 |可选    |
| enddate      | 结束时间 |可选    |
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
            "id": 105904,
            "categoryId": 647,
            "channelName": "0607直播",
            "channelSummary": "111111",
            "coverImage": "http://grocery.pptv.com/lpic/a1b/f16/5e2/c99ded12bb83eefad8d144f1ab19ebe0.png",
            "fId": 71435,
            "isPlay": 1,
            "channelId": 156589805,
            "channelType": 2,
            "createTime": "2016-06-07 11:11:09",
            "channelWebId": "0a2dnqyaqKmkmauL4K2emanhoaChoqaZ",
            "length": 0,
            "ppfeature": null,
            "userName": "meizhang@pptv.com",
            "transcodeStatus": 106,
            "liveStatus": "stopped",
            "duration": 1181,
            "realDuration": 1176,
            "screenshot": "/43/20/432094e98633f31d5c89623156589805/1.jpg",
            "liveStartTime": 1465269149056,
            "liveEndTime": 1465270371863,
            "updateTime": 1466042079000,
            "shareAuth": null,
            "nexttk": "0a2dnayaoqalmayeoKCcj-aioqCf5aeVpamcnQ",
            "subContactName": "18001700092",
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
            "live2vodStatus": 14,
            "toIboReviewStatus": 200,
            "toIboReviewOperator": null,
            "roomId": null,
            "reviewFailedReason": null,
            "siteName": "hello world test",
            "displayable": 0,
            "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaahoa%2BdoKU%3D",
            "totalFlow": "67",
            "violation": "涉黄",
            "channelTypeStr": "直播",
            "transcodeStatusStr": "待审核"
        }
    ],
    "totalnum": 1
}
</pre>

返回结果说明
----------
<pre>
vv：vv
createTime：创建时间
totalFlow：流量
violation：违规标签
censored：1已屏蔽的，0正常的
</pre>