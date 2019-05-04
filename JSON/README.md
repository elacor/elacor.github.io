<h1>Welcome To FIGHTING CLASS!</h1>
<h3>欢迎来到江外2020届五班！</h3>
<button onclick="a()" style="height:30">找同学</button>
<script>
function a(){
  q=prompt("请输入同学的姓名或者学号:")
  var json={
  "叶明航":{"name":"叶明航","sex":"♂","No":"01"},
  "01":{"name":"叶明航","sex":"♂","No":"01"},
  "关智豪":{"name":"关智豪","sex":"♂","No":"01"},
  "02":{"name":"关智豪","sex":"♂","No":"01"},
  "苏裕航":{"name":"苏裕航","sex":"♂","No":"01"},
  "03":{"name":"苏裕航","sex":"♂","No":"01"},
  "杜达聪":{"name":"杜达聪","sex":"♂","No":"01"},
  "04":{"name":"杜达聪","sex":"♂","No":"01"},
  "杜玙轩":{"name":"杜玙轩","sex":"♂","No":"01"},
  "05":{"name":"杜玙轩","sex":"♂","No":"01"}
  }
  alert("姓名:" + json[q].name + "\n性别:" + json[q].sex + "\n学号:" + json[q].No)
}
</script>
