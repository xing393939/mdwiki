获取epg分类接口
----------

接口地址
----------
  * 正式接口：http://api.pptvyun.com/pgc/api/video/list/epg-category-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName      | 用户名 |必选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "id": 139205,
            "name": "电影",
            "code": 917,
            "parent_id": 1,
            "level": 2,
            "is_deleted": 0
        }
    ],
    "err": 0,
    "msg": "getEpgCategoryList success"
}
</pre>

返回结果说明
----------
<pre>
...

用到的epg接口：
5.1获取EPG分类
</pre>