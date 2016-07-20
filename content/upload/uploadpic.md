上传图片（post跨域）
----------

接口地址
----------
  * 正式接口：上一步得到的uploadPicUrl

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| token      | token |必选|
| upload           | 文件域 |必选    |
| x      | 起始点x坐标    | 可选 |
| y      | 起始点y坐标    | 可选 |
| w      | 裁剪图片宽度 | 可选 |
| h      | 裁剪图片高度 | 可选 |
| iw      | 可视区域宽 | 可选 |

返回示例
----------
<pre>
{
    "err": 0,
    "data": "http://grocery.pptv.com/lpic/dcf/daa/0c9/a767e3c7439499706dbda1ef8e6bdcd2.png"
}
</pre>

返回结果说明
----------
<pre>
用到的接口：
http://api.grocery.pptv.com/upload_file.php（曹铮）
</pre>