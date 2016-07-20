单个限制的功能列表接口
----------

接口地址
----------
  * 正式接口：/userreview/function/restrict-info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id      | 限制id |可选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "data": {
        "root": {
            "name": "",
            "id": "1",
            "children": [
                {
                    "id": 2,
                    "name": "直播",
                    "isChecked": true,
                    "isCollapse": true,
                    "children": [
                        {
                            "id": 3,
                            "name": "创建直播",
                            "isChecked": true,
                            "isCollapse": true,
                            "children": [
                                {
                                    "id": 4,
                                    "name": "限时直播",
                                    "isChecked": true,
                                    "type": "checkbox"
                                }
                            ],
                            "type": "checkbox"
                        }
                    ]
                }
            ]   
        }
    }
}
</pre>

返回结果说明
----------
<pre>

</pre>