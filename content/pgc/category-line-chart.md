分类栏目折线图统计接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/statistics/list/category-line-chart

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey         | ppkey |必选|
| userName      | 用户名 |必选    |
| channelid      | 视频id，若不传则返回所有视频总数据 |可选    |
| startdate     | 开始时间，例20151026  |可选    |
| enddate       | 结束时间 |可选    |
| source        | 传参为web，client，mobile，all，多个用逗号隔开 |可选    |
| groupby        | 传参对应为:day，week，month |可选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": {
        "labels": [
            "电视剧",
            "电影",
            "综艺",
            "原创"
        ],
        "series": [
            {
                "name": "total",
                "data": [
                    11,
                    12,
                    13,
                    14
                ],
                "total": 1024
            },
            {
                "name": "web",
                "data": [
                    1,
                    2,
                    3,
                    4
                ],
                "total": 1024
            }
        ]
    }
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.50	栏目播放详情接口
</pre>