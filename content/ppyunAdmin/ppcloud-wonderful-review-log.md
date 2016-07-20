精彩节目审核记录接口
----------

接口地址
----------
  * 正式接口：http://172.16.0.105/pptv3/public/index.php/api/ppcloud/wonderful/review-log

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| channelwebid      | 视频id |必选    |
返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": [
        {
            "create_time": "2016-02-02 17:52",
            "operator": "lalala",
            "result": "待审核-审核不通过；三金说这视频太黄"
        }
    ]
}
</pre>

返回结果说明
----------
<pre>

</pre>