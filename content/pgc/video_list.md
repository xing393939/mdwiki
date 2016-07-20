获取用户视频接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/video/list/index

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName       | 用户名 |必选    |
| series_id      | 专辑id |可选    |
| key            | 视频名称 |可选    |
| vv            | 固定值1， |可选    |
| epg_category_id      | epg分类id |可选    |
| startdate      | 开始时间，例20151026 |可选    |
| enddate      | 结束时间 |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "id": 39035,
            "categoryId": 742,
            "channelName": "PostmenInTheMountains10",
            "channelSummary": "测试上传视频增加专辑选择",
            "fId": 62108,
            "isPlay": 1,
            "channelId": 155080839,
            "channelType": 1,
            "createTime": 1444370179000,
            "channelWebId": "0a2dnquVqKCknK-L4K2goq0",
            "length": 40406411,
            "ppfeature": "40406411_43fd8958374d46fe9b687c61cf82935214c6bdbc",
            "userName": "wengjiawei9",
            "transcodeStatus": 180,
            "liveStatus": null,
            "duration": 354,
            "liveStartTime": 1444370179104,
            "liveEndTime": null,
            "updateTime": 1445851580000,
            "shareAuth": null,
            "nexttk": "0a2dnaqZo6ecmq2eoKCcj-aipKmj5ameoKOh",
            "subContactName": null,
            "vv": null,
            "isChild": null,
            "nickName": null,
            "online": null,
            "sourceUserName": null,
            "timeLimit": null,
            "sourceUser": 0,
            "epg_category_id": 929,
            "info_status": null,
            "epgCategoryName": "焦点新闻",
            "seriesId": 71,
            "roomId": null,
            "reviewFailedReason": null,
            "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaWcoaado6k%3D",
            "showImage": "http://v.img.pplive.cn/sp160/cb/b6/cbb686dc064a2a1fb106151155080839/3.jpg",
            "channelIdEncode": "hx2GDXXbS4nsatI",
            "showUrl": "http://v.pptv.com/show/hx2GDXXbS4nsatI.html"
        }
    ],
    "err": 0,
    "msg": null,
    "totalnum": 1
}
</pre>

返回结果说明
----------
<pre>
...

用到pgc的接口：
5.10视频列表(用于用户操作页面)
</pre>