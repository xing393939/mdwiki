排行统计TOP接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/statistics/list/top

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey         | ppkey |必选|
| userName      | 用户名 |必选    |
| type          | videoPlay(视频排行)，categoryPlay(分类排行)，默认为videoPlay |必选    |
| top           | 10,25,50 |必选    |
| orderby       | vv，svv，uv，pwt，income |必选    |
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
            "channelname": "电视剧",
            "vv": "23",
            "svv": "23",
            "uv": "13",
            "pwt": "246",
            "income": "50.2",
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