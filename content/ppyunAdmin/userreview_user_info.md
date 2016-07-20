单个用户详情接口
----------

接口地址
----------
  * 正式接口：/userreview/user/info

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| userName      | 用户名 |必选    |

返回示例
----------
<pre>
{
    "err": 0,
    "msg": "success",
    "totalnum": 5,
    "data": {
        "userName": "hongleiqiu@pptv.com",
        "siteName": "testsitename",
        "siteDomain": "testdomain",
        "contactName": "testcontact",
        "phone": "1231231",
        "qq": null,
        "userStatus": 1,
        "createTime": "2016-02-01 04:41:32",
        "id": 678,
        "reviewLevel": 0,
        "toPptv": 0,
        "toIbo": 0,
        "parentId": 675,
        "nickName": null,
        "email": null,
        "isChild": 1,
        "subuserauth": 1,
        "passportname": null,
        "needLive2vod": 1,
        "needEncrypt": 0,
        "channelNumber": 0,
        "reviewStatus": "0",
        "reviewStatusStr": "未审核",
        "isPaidStr": "付费",
        "accountStatusStr": "超限",
        "trafficStatusStr": "0/1000G",
        "spaceStatusStr": "0/1000G",
        "licensePic": "http://grocery.pptv.com/lpic/d53/f5f/cf6/dc50589bf10bdd0369b61d00d2d8a02f.png"
    }
}
</pre>

返回结果说明
----------
<pre>
"siteName"：公司名称
"license_pic": 营业执照图片地址
</pre>