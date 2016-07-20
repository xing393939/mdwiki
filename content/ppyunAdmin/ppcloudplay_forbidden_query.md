禁词库查询接口（get请求）
----------

接口地址
----------
  * 测试接口：http://172.16.0.105/pptv3/public/index.php/ppcloudplay/forbidden/list
  * 正式接口：http://admin.cloud.pptv.com/public/index.php/ppcloudplay/forbidden/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| word      | 关键字           |可选    |
| level      | 等级（1，2，3） |可选    |
| page_size      | 每页条数，默认20条 |可选    |
| page_no      | 页数 |可选    |

返回示例
----------
<pre>
{
    "data": [
        {
          "id": 27736,
          "word": "1612938793",
          "lastModified": "2015-01-07",
          "level": 1
        }
    ],
    "message": "请求成功",
    "code": 0,
    "totalRecords": 66,
    "currentPageNO": "1"
}
</pre>

返回结果说明
----------
<pre>
word    关键字
level   等级
id      自增id
lastModified  最后修改时间
</pre>