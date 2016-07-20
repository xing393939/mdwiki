视频折线图统计接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/statistics/list/video-line-chart

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey         | ppkey |必选|
| userName      | 用户名 |必选    |
| type          | vv，svv, uv，pwt，income（播放数，有效播放次数，访客数，日均观看时长） |必选    |
| channelid      | 视频id，若不传则返回所有视频总数据 |可选    |
| startdate     | 开始时间，例20151026  |可选    |
| enddate       | 结束时间 |可选    |
| groupby        | 传参对应为:day，week，month |可选    |
| source        | 传参为web，client，mobile，all，多个用逗号隔开 |可选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": {
        "labels": [
            "2015-10-01",
            "2015-10-02",
            "2015-10-03",
            "2015-10-04"
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
5.49	视频播放信息接口
</pre>