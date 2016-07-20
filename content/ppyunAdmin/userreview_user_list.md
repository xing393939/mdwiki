用户列表接口
----------

接口地址
----------
  * 正式接口：/userreview/user/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userName      | 用户名           |可选    |
| siteName      | 网站名称           |可选    |
| phone      | 手机号           |可选    |
| review_status      | 0:未审核 100:不通过 200:通过 |可选    |
| is_license_pic_uploaded | 1已上传照片 0没有| 可选 |  
| usercanaltype       | 用户类型，0终端,1渠道,2渠道客，默认是空显示全部 |可选    |
| pagesize      | 每页条数，默认10条 |可选    |
| pageno      | 页数 |可选    |

返回示例
----------
<pre>
{
    "data": [
        {
            "userName": "1111@pptv.com",
            "siteName": "12321",
            "siteDomain": "http://www.baidu.com",
            "contactName": "123",
            "phone": "13543321234",
            "qq": "112321",
            "userStatus": 0,
            "createTime": "2015-08-05 07:32:14",
            "id": 532,
            "reviewLevel": 0,
            "toPptv": 0,
            "toIbo": 0,
            "parentId": null,
            "nickName": null,
            "email": null,
            "isChild": 0,
            "subuserauth": 0,
            "yesterdayUV": null,
            "yesterdayVV": null,
            "yesterdayWT": null,
            "totalSpace": null,
            "usedSpace": null,
            "totalVideoCount": null,
            "reviewStatusStr": "未审核",
            "vocationNameChinese": "普通",
            "vocation": "1",
            "isPaidStr": "试用",
            "licensePic": null,
            "payTypeStr": "后付费",
            "postPaidStartTime": "2016-06-01"
        }
    ],
    "message": "请求成功",
    "code": 0,
    "currentPageNO": "1",
    "totalRecords": 205
}
</pre>

返回结果说明
----------
<pre>
"userName": 用户名
"contactName": 联系人
"siteName": 网站名称
"phone": 手机号
"reviewStatusStr": 审核状态
"vocationNameChinese": 行业
"vocation": 行业id
"isPaidStr": 用户类型
</pre>