修改用户上报接口
----------

接口地址
----------
  * 正式接口：/userreview/report/user-report-edit

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| reportid       | 上报id |可选    |
| status | 处理状态  0未处理，1处理中，2处理完成 |可选    |
| reason| 故障原因  |可选    |
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
2.119	修改用户上报
</pre>