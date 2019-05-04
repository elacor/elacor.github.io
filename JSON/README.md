<h1>Welcome To FIGHTING CLASS!</h1>
<h3>欢迎来到江外2020届五班！</h3>
<button onclick="a()" style="height:30">找同学</button>
<script>
function a(){
  q=prompt("请输入同学的姓名或者学号:")
  var json={
    "叶明航": [{"sex": "♂","No.": "01"}]
  }
  alert(json[q].sex)
}
</script>
