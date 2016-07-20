保存视频接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/video/list/save-channel

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
| channelname      | 视频名 |必选    |
| summary     | 视频描述 |可选    |
| series_id      | 专辑id |必选    |
| epg_category_id      | epg分类id |必选    |
| ppfeature      | 视频特征 |必选    |
| size     | 文件大小，单位Byte |必选    |

返回示例
----------
<pre>
{
    "data": {
        "id": 39612,
        "categoryId": 742,
        "userId": 497,
        "subUserId": 497,
        "channelName": "testname",
        "channelSummary": "testsummary",
        "coverImage": "",
        "fId": 4413,
        "isPlay": 1,
        "channelId": 155082371,
        "channelType": 1,
        "createTime": 1447153456645,
        "channelWebId": "0a2dnquVqKKfoKeL4K2goq0",
        "length": 600,
        "ppfeature": "26246026_b0daa192eb9c37490a1aae9787dfb1059d1310cb",
        "userName": null,
        "transcodeStatus": 150,
        "liveStatus": null,
        "duration": 0,
        "screenshot": null,
        "vod_status": 150,
        "file_status": 101,
        "extend": {
            "title": "testname",
            "username": "wengjiawei9"
        },
        "epg_category_id": 2405,
        "info_status": null,
        "pptvsPlayStr": "pptvs://4NzN4tvXr%2BTl2dui4ODi2NqL09jN1%2BTK3M%2FVzbOWpaWcoaiYp6E%3D"
    },
    "err": 0,
    "msg": "addUserChannel success"
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.8上传视频
</pre>