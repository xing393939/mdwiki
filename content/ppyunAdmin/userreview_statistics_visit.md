[流量统计]单个用户详情接口
----------

接口地址
----------
  * 正式接口：/userreview/statistics/visit

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id     | 用户id |必选    |
| userName     |用户名|必选    |

返回示例
----------
<pre>
{
    "data": {
        "userName": "meili13@pptv.com",
        "contactName": "testcontact",
        "siteName": "testsitename13",
        "phone": "1231231",
        "starttime": "2014-01-01",
        "endtime": "2016-12-31",
        "uvTotalResult": 0,
        "vvTotalResult": 0,
        "wtTotalResult": 0
    },
    "message": "success",
    "code": 0
}
</pre>

返回结果说明
----------
<pre>

</pre>