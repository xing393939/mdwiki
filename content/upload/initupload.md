创建节目并初始化上传（post跨域）
----------

接口地址
----------
  * 正式接口：上一步得到的nextUrl

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| token      | token |必选|
| files[]           | 5块文件 |必选    |
| size           | 文件大小 |必选    |
| channelname    | 视频名 |必选|
| summary        | 视频描述 |可选    |
| categoryid      | 分类 |可选|
| coverimg      | 封面图url |可选|

返回示例
----------
<pre>
{
    "data": {
        "nextUrl": "http://ppyun.ugc.upload.pptv.com/php/getRange.php",
        "channelWebId": "0a2dnquZpqmemq-L4K2hnajhpKGenaw",
        "coverImage": "http://grocery.pptv.com/lpic/ea7/a31/013/de8660322896b27530d31d82a0aa7bd0.jpg",
        "ppfeature": "27220579_f99293c12424e20303b5dbd8de771185638312ba",
        "fid": 64828
    },
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
用到PP云的对外接口：
2.2.6 上传点播视频接口
</pre>