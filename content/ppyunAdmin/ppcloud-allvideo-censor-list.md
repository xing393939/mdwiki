屏蔽历史记录列表接口
----------

接口地址
----------
  * 正式接口：http://admin.cloud.ppqa.com/public/index.php/api/ppcloud/allvideo/censored-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
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
            "id": 105051,
            "categoryId": 1056,
            "channelName": "假面骑士铠武 - 第2集_demo",
            "channelSummary": null,
            "coverImage": "",
            "fId": 69020,
            "isPlay": 1,
            "channelId": 156587371,
            "channelType": 1,
            "createTime": "2016-04-18 13:12:43",
            "channelWebId": "0a2dnqyaqKefoKeL4K2hoqrhoaChmauW",
            "length": 10200830,
            "ppfeature": "10200830_ec0942d4e06421ad11a5ff540038e0ceff147986",
            "userName": "jiahuixu@pptv.com",
            "transcodeStatus": 0,
            "liveStatus": null,
            "duration": 1589,
            "realDuration": 1589,
            "screenshot": "/37/76/3776ecfd70633573a53d890156587371/3.jpg",
            "liveStartTime": 1460956351553,
            "liveEndTime": null,
            "updateTime": 1460962448000,
            "shareAuth": null,
            "nexttk": "0a2dnayVqaWinKyYoKCcj-aipamg5aeVpaChmg",
            "subContactName": "",
            "vv": null,
            "isChild": 0,
            "nickName": null,
            "online": null,
            "sourceUserName": "aaaa",
            "timeLimit": null,
            "timePreset": null,
            "sourceUser": 0,
            "epg_category_id": null,
            "info_status": null,
            "epgCategoryName": null,
            "seriesId": 0,
            "seriesName": null,
            "toibo": 0,
            "live2vodStatus": null,
            "toIboReviewStatus": 0,
            "toIboReviewOperator": null,
            "roomId": null,
            "reviewFailedReason": null,
            "siteName": "aaa1",
            "displayable": 0,
            "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaahoa2Yp6E%3D",
            "totalFlow": "67",
            "violation": "涉黄",
            "channelTypeStr": "点播",
            "transcodeStatusStr": "未知",
            "reviewer": "shaohuayu",
            "reviewResult": "政治敏感之类的原因",
            "censored": 1
        }
    ],
    "totalnum": 49
}
</pre>

返回结果说明
----------
<pre>
createTime：创建时间
violation：违规标签
censored：1已屏蔽的，0正常的
reviewer: 屏蔽操作人
reviewResult: 屏蔽原因
</pre>