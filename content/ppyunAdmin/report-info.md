单个举报视频详情接口（get请求）
----------

接口地址
----------
  * 测试接口：http://172.16.0.105/pptv3/public/index.php/reportvideo/reportvideo/info
  * 正式接口：http://admin.cloud.pptv.com/public/index.php/reportvideo/reportvideo/info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| id      | 举报id |必选|
返回示例
----------
<pre>
{
    "data": {
        "fid": 31507,
        "videoName": "ABC",
        "status": "已处理",
        "reportTime": "2014-04-20",
        "reportType": "版权侵犯",
        "reportDesc": "侵犯其他公司版权",
        "platfrom": "Android独立版本",
        "userName": "2567@sina.com",
        "playingUrl": "http://172.20.4.193/w/afb5bb748232aba3ce11537bbec1e26f.mp4?k=caf23606baa90dbf65dcb565d82a0e0e-d8ed-1440573264%26limit_rate%3D100k&type=web.cloudplay",
        "getScreenshotArray": [
            "http: //panoimage.pptv.com/2/150014179_6_10x10_0_720.jpg"
        ],
        "videoTimeLength": "00: 42: 23",
        "failedReason": {
            "51": "有暴力镜头",
            "53": "少儿不易"
        },
        "lastOperation": {
            "deal_type": "adult_video",
            "deal_status": "unpassed",
            "failed_reason": 33
        }
    },
    "message": "success",
    "code": 0
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
reportDesc: 举报说明
platfrom: 举报来源
userName: 举报用户
playingUrl: 播放地址
videoTimeLength: 播放时长，秒为单位
failedReason: 失败原因列表
lastOperation: 最后一次审核操作信息
</pre>