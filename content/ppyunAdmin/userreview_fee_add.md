计费添加接口
----------

接口地址
----------
  * 正式接口：/userreview/fee/add

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| user_id      | 用户id |可选    |
| traffic_flow      | 购买流量，单位G |可选    |
| storage_space      | 购买空间，单位G |可选    |
| discount   | 折扣，如0.2 |可选    |
|price	|价格|可选    |
|fee	|折后价|可选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": []
}
</pre>

返回结果说明
----------
<pre>
..
</pre>