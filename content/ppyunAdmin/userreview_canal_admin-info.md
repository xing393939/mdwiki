单个admin管理员接口
----------

接口地址
----------
  * 正式接口：/userreview/canal/admin-info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id    | 用户id | 必选|

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
                    "name": "渠道分类",
                    "children": [
                        {
                            "id": "C1",
                            "name": "C1",
                            "isChecked": true,
                            "type": "checkbox"
                        },
                        {
                            "id": "C2",
                            "name": "C2",
                            "isChecked": false,
                            "type": "checkbox"
                        }
                    ]
                },
                {
                    "id": 0,
                    "name": "渠道",
                    "isChecked": false,
                    "type": "checkbox"
                }
            ]
        }
    }
}
</pre>

返回结果说明
----------
<pre>
...
</pre>