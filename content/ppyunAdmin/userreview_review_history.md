单个用户的审核历史接口
----------

接口地址
----------
  * 正式接口：/userreview/user/review-history

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userid     | 用户id |必选    |

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
            "typeStr": "审核",
            "price": "150",
            "traffic_flow": "200G",
            "storage_space": "300G",
            "result": "资质审核成功",
            "license_pic": "http://grocery.pptv.com/lpic/d53/f5f/cf6/dc50589bf10bdd0369b61d00d2d8a02f.png"
        },
        {
            "id": 2,
            "userId": 512,
            "createTime": "2016-02-09 10:20",
            "typeStr": "审核",
            "price": "150",
            "traffic_flow": "200G",
            "storage_space": "300G",
            "result": "资质审核成功",
            "license_pic": "http://grocery.pptv.com/lpic/d53/f5f/cf6/dc50589bf10bdd0369b61d00d2d8a02f.png"
        }
    ]
}
</pre>

返回结果说明
----------
<pre>

</pre>