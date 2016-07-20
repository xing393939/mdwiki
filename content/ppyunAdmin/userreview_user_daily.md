[费用统计]单个用户日报表接口
----------

接口地址
----------
  * 正式接口：/userreview/statistics/daily

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userid         | 用户id |必选|
| type      | type=1前一天，=2上个月 |可选    |
| starttime      | 开始时间，如2015-02-05           |可选    |
| endtime      | 结束时间 |可选    |
| pagesize      | 每页条数，默认10条 |可选    |
| pageno      | 页数 |可选    |

返回示例
----------
<pre>
{
    "data": [
        {
            "date": "151013",
            "space": 0,
            "spacefee": 0,
            "flow": 0,
            "flowfee": 0
        }
    ],
    "message": "请求成功",
    "code": 0,
    "currentPageNO": "1",
    "totalRecords": 205
}
</pre>

返回结果说明
----------
<pre>
"space": 空间,
"spacefee": 空间费用,
"flow": 流量,
"flowfee": 流量费用
</pre>