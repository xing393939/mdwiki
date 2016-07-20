视频列表接口（get请求）
----------

接口地址
----------
  * 正式接口：http://ppyun.ugc.upload.pptv.com/php/api_channel_list.php

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username      | 用户名 |必选|
| apikey           | 接口key，用户登录pp云后可获取 |必选    |
| key      | 视频名 | 可选 |
| pagenum       | 页数，默认1     | 可选 |
| pagesize      | 每页个数，默认10 | 可选 |

返回示例
----------
<pre>
{
    "err": 0,
    "data": [
        {
            "channelId": 155494452,
            "fid": 64889,
            "channelName": "name",
            "channelSummary": "summary",
            "coverImage": "http://grocery.pptv.com/lpic/ea7/a31/013/de8660322896b27530d31d82a0aa7bd0.jpg",
            "transcodeStatus": 0,
            "statusStr": "创建中"
        }
    ],
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>

</pre>