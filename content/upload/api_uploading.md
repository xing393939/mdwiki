获取上传进度、上传范围（post跨域）
----------

接口地址
----------
  * 正式接口：http://ppyun.ugc.upload.pptv.com/php/api_uploading.php

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| fid      | 文件id |必选|
| ppfeature   | 文件特征码 |必选    |
返回示例
----------
<pre>
{
    "data": {
        "status": 0,
        "fileSize": 26246061,
        "finished": 0,
        "ranges": {
            "start": 0,
            "end": 4194304
        }
    },
    "err": 0
} 
</pre>

返回结果说明
----------
<pre>
...
</pre>