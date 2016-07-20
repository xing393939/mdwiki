禁词库添加接口（get请求）
----------

接口地址
----------
  * 测试接口：http://172.16.0.105/pptv3/public/index.php/ppcloudplay/forbidden/add
  * 正式接口：http://admin.cloud.pptv.com/public/index.php/ppcloudplay/forbidden/add

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| word      | 关键字           |必选    |
| level      | 等级（1，2，3） |必选    |

返回示例
----------
<pre>
{
    "code": 0,
    "message": 'success',
    "data": null
}
</pre>

返回结果说明
----------
<pre>
....
</pre>