分类栏目占比接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/statistics/list/category-ratio

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey         | ppkey |必选|
| userName      | 用户名 |必选    |
| type          | 传参为vv,uv,pwt,income,channelnum |必选    |
| startdate     | 开始时间，例20151026  |可选    |
| enddate       | 结束时间 |可选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": [
        [
            "电视剧",
            45
        ],
        [
            "电影",
            26.8
        ]
    ]
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.57	分类栏目占比接口
</pre>