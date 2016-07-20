[费用统计]单个用户详情接口
----------

接口地址
----------
  * 正式接口：/userreview/statistics/info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userid         | 用户id |必选|
| username      | 用户名 |必选|
| type      | type=1前一天，=2上个月 |可选    |
| starttime      | 开始时间，如2015-02-05           |可选    |
| endtime      | 结束时间 |可选    |
返回示例
----------
<pre>
{
    "data": {
        "userName": "timxu@pplive.com",
        "siteName": "xx",
        "siteDomain": "http://www.xx.com",
        "contactName": "xx",
        "phone": "12345678956",
        "qq": "",
        "userStatus": 1,
        "createTime": 1409889252000,
        "id": 563,
        "reviewLevel": 0,
        "toPptv": 0,
        "toIbo": 0,
        "parentId": null,
        "nickName": "xx",
        "email": null,
        "isChild": 0,
        "subuserauth": 1,
        "passportname": null,
        "needLive2vod": 1,
        "needEncrypt": 0,
        "starttime": "2015-01-01",
        "endtime": "2015-02-01",
        "totalSpace": 0,
        "totalSpaceFee": 0,
        "totalFlow": 0,
        "totalFlowFee": 0,
        "totalFee": 0
    },
    "message": "请求成功",
    "code": 0
}
</pre>

返回结果说明
----------
<pre>
"starttime": 开始时间
"endtime": 结束时间
"totalSpace": 空间
"totalSpaceFee": 空间费用
"totalFlow": 流量
"totalFlowFee": 流量费用
"totalFee": 总费用
</pre>