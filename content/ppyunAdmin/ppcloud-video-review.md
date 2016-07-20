视频审核接口
----------

接口地址
----------
  * 正式接口：http://172.16.0.105/pptv3/public/index.php/api/ppcloud/video/review

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id      | 视频id |必选    |
| user_id      | user_id |必选    |
| review      | 审核状态 nopass:不通过  pass:通过 |必选    |
| reason      | 不通过原因，字符串 |可选    |
返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": []
}
</pre>

返回结果说明
----------
<pre>

</pre>