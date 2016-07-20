计费配置列表接口
----------

接口地址
----------
  * 正式接口：/userreview/fee/config-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|


返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": [
        {
            "package_id": 512,
            "userIsPaidStr": "试用用户",
            "reviewStatusStr": "未审核",
            "trafficFlow": "200G",
            "storageSpace": "300G"
        }
    ]
}
</pre>

返回结果说明
----------
<pre>
2.80	获取计费管理列表
</pre>