禁词库导入excle接口（post请求）
----------

接口地址
----------
  * 测试接口：http://172.16.0.105/pptv3/public/index.php/ppcloudplay/forbidden/upload
  * 正式接口：http://admin.cloud.pptv.com/public/index.php/ppcloudplay/forbidden/upload

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| excle      | 二进制数据           |必选    |
| cb      | 返回的js函数函数名，如callback           |必选    |

返回示例
----------
<pre>
<script>parent.callback('{"code": 0,"message": 'success',"data": null}')</script>
</pre>

返回结果说明
----------
<pre>
....
</pre>