用户历史费用列表接口
----------

接口地址
----------
  * 正式接口：/userreview/fee/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userId      | 用户ID |必选    |
| type	| 默认是全部，register:注册历史记录 review:审核历史记录 buying:购买历史记录|必选    |


返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "totalnum": 5,
    "data": [
        {
            "id": 2,
            "userId": 512,
            "createTime": "2016-02-09 10:20",
            "typeStr": "购买",
            "price": "150",
            "traffic_flow": "200G",
            "storage_space": "300G",
            "result": "流量:1000G，存储1000G，金额：50RMB，折扣：0.5"
        }
    ]
}
</pre>

返回结果说明
----------
<pre>
..
</pre>