分类栏目占比三个总数接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/statistics/list/category-summary-data

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey         | ppkey |必选|
| userName      | 用户名 |必选    |
| type          | 传参为vv,uv,pwt,income,channelnum |可选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": {
        "total": "8918645",
        "week": "4645",
        "month": "76456"
    }
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.57	分类栏目占比接口
</pre>