<h1>Welcome To FIGHTING CLASS!</h1>
<h3>欢迎来到江外2020届五班！</h3>
<button onclick="a()" style="height:30">找同学</button>
<script>
function a(){
  q=prompt("请输入同学的姓名或者学号:")
  var json={
    "name": "BeJson",
    "url": "http://www.bejson.com",
    "page": 88,
    "isNonProfit": true,
    "address": {
        "street": "科技园路.",
        "city": "江苏苏州",
        "country": "中国"
    },
    "links": [
        {
            "name": "Google",
            "url": "http://www.google.com"
        },
        {
            "name": "Baidu",
            "url": "http://www.baidu.com"
        },
        {
            "name": "SoSo",
            "url": "http://www.SoSo.com"
        }
    ]
}
  alert(json[q])
}
</script>
