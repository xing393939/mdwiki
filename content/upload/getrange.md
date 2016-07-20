获取上传进度、上传范围（post跨域）
----------

接口地址
----------
  * 正式接口：接口3的nextUrl

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| token      | token|必选|
| fid        | 文件id |必选|
| ppfeature   | 文件特征码 |必选    |
返回示例
----------
<pre>
{
    "data": {
        "nextUrl": "http://ppyun.ugc.upload.pptv.com/php/uploadRange.php?token=x&fid=x&ppfeature=x&start=0&end=0",
        "status": 0,
        "fileSize": 26246061,
        "finished": 0
    },
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
用到云盘的接口：
1.1.3	获得上传范围v2
1.1.5	提交md5
1.1.6	提交额外特征
</pre>