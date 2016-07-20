视频审核报告用户列表接口
----------

接口地址
----------
  * 正式接口：/userreview/report/user-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username       | 用户名，可模糊搜索 |可选    |
| userstatus | 0:已删除,1:使用中 |可选    |
| sitename     | 网站名称  |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": [
        {
            "userName": "yuhanlai@pptv.com",
            "isDeleted": "0",
            "userId": "25",
            "siteName": "pptv",
            "illegalVideoNum": "258",
            "illegalVideoRatio": "90%",
            "isDeletedStr": "使用中"
        }
    ]
}
</pre>

返回结果说明
----------
<pre>
...
</pre>