获取token（post请求）
----------

接口地址
----------
  * 正式接口：http://ppyun.ugc.upload.pptv.com/php/uploadAuth.php

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username      | username |必选|
| apikey        | apikey |必选    |
| uploadpic     | 值为1则返回上传图片的地址，默认不返回   | 可选 |

返回示例
----------
<pre>
{
    "data": {
        "nextUrl": "http://ppyun.ugc.upload.pptv.com/php/initUpload.php",
        "uploadPicUrl": "http://ppyun.ugc.upload.pptv.com/php/uploadPic.php?app=lpic&tk=MW7DVNBN7ULbRuI7dHEid&prod=pgc_idcard"
        "token": "be88b6c34d7c2dcf01346864108c9817"
    },
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
用到PP云对外接口：
2.2.18 获取带token的图片上传url（段准）
</pre>