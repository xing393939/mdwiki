第三方获取token的php示例
----------
在使用pp云无插件上传的JS库之前，需要先从后端请求接口获取上传的token供js使用\\
<pre>
<?php
function send_post($url, array $post_data = array())
{
    $ch = curl_init();
    curl_setopt($ch, CURLOPT_URL, $url);
    curl_setopt($ch, CURLOPT_POSTFIELDS, $post_data);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
    curl_setopt($ch, CURLOPT_TIMEOUT, 75);
    curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, false);
    $data = curl_exec($ch);
    curl_close($ch);
    return $data;
}

$url = 'http://ppyun.ugc.upload.pptv.com/php/uploadAuth.php';
$post_data = array(
    'username' => 'scdddk@163.com',
    'apikey' => 'FBBA0D39FA8F0A34814B1DDC24FCBB42',
);
$arr = json_decode(send_post($url, $post_data), true);
?>
<html>
<head>
    <script type="text/javascript">
        var TOKEN = '<?php echo $arr['data']['token']; ?>';
        var INIT_URL = '<?php echo $arr['data']['nextUrl']; ?>';
    </script>
</head>
<body>
</body>
</html>
</pre>