举报视频列表接口（get请求）
----------

接口地址
----------
  * 测试地址：http://172.16.0.105/pptv3/public/index.php/reportvideo/reportvideo/list
  * 正式地址：http://admin.cloud.pptv.com/public/index.php/reportvideo/reportvideo/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| deal_status      | 处理状态，值为0为未处理，为1为已处理，为空则显示全部  |必选    |
| name      | 视频名           |可选    |
| fid      | 视频fid |可选    |
| month      | 查询月份，格式如2015-08，为空则显示全部           |可选    |
| page_size      | 每页条数，默认20条 |可选    |
| page_no      | 页数 |可选    |

返回示例
----------
<pre>
{
    "data": [
        {
            "id": 40,
            "userName": "qatest",
            "status": "已处理",
            "fid": 31570,
            "reportTime": "2015-09-17 12:13:12",
            "videoName": "qavideo",
            "reportType": "政治有害",
            "reportDesc": "reportDesc",
            "platfrom": "PC",
            "json": "{\"mb\":1}",
            "reportForm": "PC"
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
fid  文件ID
videoName：视频名称
status: 处理状态
reportTime: 举报时间,
reportType: 举报类型
reportExplain: 举报说明
reportDesc: 举报来源
userName: 举报用户
</pre>