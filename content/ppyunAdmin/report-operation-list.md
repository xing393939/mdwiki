单个举报视频的操作记录接口（get请求）
----------

接口地址
----------
  * 测试接口：http://172.16.0.105/pptv3/public/index.php/reportvideo/reportvideo/operation-list
  * 正式接口：http://admin.cloud.pptv.com/public/index.php/reportvideo/reportvideo/operation-list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id      | 举报id |必选|
返回示例
----------
<pre>
{
    "data": [
        {
            "id": 1,
            "fid": 156,
            "username": "xingchen",
            "video_category": "政治敏感",
            "review_result": "未通过",
            "created_at": "2015-08-24 02:25:12"
        }
    ],
    "message": "success",
    "code": 0
}
</pre>

返回结果说明
----------
<pre>
    username: 操作人员
    video_category: 视频分类
    review_result: 审核结果
    created_at: 操作时间
</pre>