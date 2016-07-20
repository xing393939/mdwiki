获取用户专辑接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/album/list/index

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
| series_name      | 专辑名，精确匹配 |可选    |
| epg_category_id      | epg分类id |可选    |
| startdate      | 开始时间，例20151026 |可选    |
| enddate      | 结束时间 |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "id": 68,
            "userId": 497,
            "createTime": 1438239925000,
            "seriesName": "我的专辑1",
            "epgCategoryId": 930,
            "isPlay": 1,
            "contractId": 154,
            "channelNumber": 2,
            "status": 1,
            "epgCategoryName": "明星",
            "userInfoName": "晨晨",
            "userName": "wengjiawei9",
            "totalFileSize": 0,
            "isLock": 1
        }
    ],
    "err": 0,
    "msg": null,
    "totalnum": 4
}
</pre>

返回结果说明
----------
<pre>
...

用到pgc的接口
5.33专辑列表
</pre>