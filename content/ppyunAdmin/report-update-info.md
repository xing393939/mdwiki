单个举报视频修改审核状态接口（get请求）
----------

接口地址
----------
  * 测试接口：http://172.16.0.105/pptv3/public/index.php/reportvideo/reportvideo/update-info
  * 正式接口：http://admin.cloud.pptv.com/public/index.php/reportvideo/reportvideo/update-info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| report_id      | 举报记录的唯一id |必选|
| deal_type      | 视频审核分类 |必选|
| deal_status      | 视频审核状态，passed和unpassed |必选|
| failed_reason      | 失败原因的id |必选|

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