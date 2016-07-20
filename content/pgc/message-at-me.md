与我相关的消息接口
----------

接口地址
----------
  * 新接口：http://api.pptvyun.com/pgc/api/message/list/at-me

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| PPKey      | ppkey |必选|
| userName   | 用户名 |必选    |
| is_readed  | =1标记为已读| 选填 |
| pageno        | 页码 |必选    |
| pagesize        | 每页个数 |必选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "relationId": 1,
            "messageTitle": "XX（视频名）视频审核未通过",
            "isReaded": 0,
            "messageCreateTime": "2016-1-7",
            "dialogInfo": {
                "dialogTitle": "留言标题",
                "dialogContent": "留言",
                "createTime": "2016-02-29"
            }
        }
    ],
    "atMeUnread": 2,
    "systemUnread": 1,
    "totalnum": 12,
    "err": 0,
    "msg": "success"
}
</pre>

返回结果说明
----------
<pre>
...

用到pgc的接口：
5.66	查询商户端消息列表
5.67	查询消息件数
5.64	更新商户端消息(删除/已读状态)
</pre>