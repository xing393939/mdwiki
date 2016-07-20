渠道账号列表接口
----------

接口地址
----------
  * 正式接口：/userreview/canal/list

请求参数说明
----------
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| username            | 用户名 |可选    |
| sitename            | 网站名称 |可选    |
| phone      | 手机号  |可选    |
| pageno      | 页数，默认为1 |可选    |
| pagesize      | 每页条数，默认为10 |可选    |
返回示例
----------
<pre>
{
    "data": [
        {
            "userName": "xuxin_kgb@sina.cn",
            "siteName": "12 ",
            "siteDomain": "",
            "contactName": "dsa ",
            "phone": null,
            "qq": null,
            "userStatus": 1,
            "createTime": "2016-05-12 14:46:21",
            "id": 809,
            "reviewLevel": 0,
            "toPptv": 0,
            "toIbo": 1,
            "parentId": null,
            "nickName": null,
            "email": "xuxin_kgb@sina.cn",
            "isChild": 0,
            "subuserAuth": 0,
            "passportName": "xuxin_kgb@sina.cn",
            "needLive2vod": 1,
            "needEncrypt": 0,
            "userType": 0,
            "channelNumber": 0,
            "isPaid": 0,
            "vocation": 1,
            "accountStatus": 200,
            "trafficUsed": 0,
            "trafficTotal": 1000000000000000,
            "spaceUsed": 0,
            "spaceTotal": 1000000000000000,
            "reviewStatus": 0,
            "licensePic": null,
            "reviewFailedReason": null,
            "menus": null,
            "vocationNameChinese": "普通",
            "emailValidateStatus": 200,
            "phoneValidateStatus": 0,
            "toIboReviewLevel": 1,
            "yesterdayUV": null,
            "yesterdayVV": null,
            "yesterdayWT": null,
            "totalSpace": null,
            "usedSpace": null,
            "totalVideoCount": null,
            "siteNameInitial": 0,
            "manage_tag": "<a href=\"http://localhost/scc/public/index.php/userreview/user/subuser?id=xuxin_kgb@sina.cn&subuserauth=1\">开启子账户</a>",
            "reviewStatusStr": "未审核",
            "isPaidStr": "试用",
            "accountStatusStr": "正常",
            "trafficStatusStr": "0G/无限制",
            "spaceStatusStr": "0G/无限制",
            "toIboTag": "露出 / <a class='ppBtn' onclick='return confirm(\"当日只能修改一次哦！确认修改吗？\")' href=\"http://localhost/scc/public/index.php/userreview/user/edit-to-ibo?id=xuxin_kgb@sina.cn&toibo=0\">不露出</a>",
            "toIboReviewLevelTag": "普通 / <a class='ppBtn' onclick='return confirm(\"当日只能修改一次哦！确认修改吗？\")' href=\"http://localhost/scc/public/index.php/userreview/user/edit-to-ibo-level?id=xuxin_kgb@sina.cn&to_ibo_review_level=0\">设为免审</a>",
            "userCanalType": 2,
            "userCanalTypeStr": "渠道客",
            "canalUserName": "jiahuixu@pptv.com",
            "trafficUsedOfTen": "23G",
            "canalTypeStr": "C1",
            "customerNum": 12
        }
    ],
    "msg": "请求成功",
    "err": 0,
    "totalnum": 280
}
</pre>

返回结果说明
----------
<pre>
"userCanalType": 0终端，1渠道，2渠道客 
"userCanalTypeStr": 用户类型
"canalUserName": 所属渠道商
"trafficUsedOfTen": 10天累计使用流量
"canalTypeStr": 渠道分类
"customerNum": 12 渠道客数量
</pre>