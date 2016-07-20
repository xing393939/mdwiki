用户视频列表接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/statistics/list/video-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey         | ppkey |必选|
| userName      | 用户名 |必选    |
| channelid      | 视频id，若不传则返回所有视频总数据 |可选    |
| startdate     | 开始时间，例20151026  |可选    |
| enddate       | 结束时间 |可选    |
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
            "channelid": "785246",
            "channelname": "机器人阿波罗",
            "vv": "23",
            "accumulativevv": "785",
            "uv": "13",
            "accumulativeuv": "562",
            "pwt": "246",
            "accumulativepwt": "785246",
            "income": "50.2",
            "accumulativeincome": "532"
        },
        {
            "channelid": "785247",
            "channelname": "机器人阿波罗",
            "vv": "23",
            "accumulativevv": "785",
            "uv": "13",
            "accumulativeuv": "562",
            "pwt": "246",
            "accumulativepwt": "785246",
            "income": "50.2",
            "accumulativeincome": "532"
        }
    ],
    "totalnum": 50
}
</pre>

返回结果说明
----------
<pre>
...

用到的pgc接口：
5.55	视频播放排行接口（客户端）
</pre>