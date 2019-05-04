<h1>Welcome To FIGHTING CLASS!</h1>
<h3>欢迎来到江外2020届五班！</h3>
<button onclick="a()" style="height:30">找同学</button>
<script>
function a(){
  q=prompt("请输入同学的姓名或者学号:")
  var json={
  "叶明航":{"name":"叶明航","sex":"♂","No":"01"},
  "01":{"name":"叶明航","sex":"♂","No":"01"},
  "关智豪":{"name":"关智豪","sex":"♂","No":"02"},
  "02":{"name":"关智豪","sex":"♂","No":"02"},
  "苏裕航":{"name":"苏裕航","sex":"♂","No":"03"},
  "03":{"name":"苏裕航","sex":"♂","No":"03"},
  "杜达聪":{"name":"杜达聪","sex":"♂","No":"04"},
  "04":{"name":"杜达聪","sex":"♂","No":"04"},
  "杜玙轩":{"name":"杜玙轩","sex":"♂","No":"05"},
  "05":{"name":"杜玙轩","sex":"♂","No":"05"},
  "杨明辉":{"name":"杨明辉","sex":"♂","No":"06"},
  "06":{"name":"杨明辉","sex":"♂","No":"06"},
  "不数字":{"name":"不数字","sex":"♂","No":"07"},
  "07":{"name":"不数字","sex":"♂","No":"07"},
  "肖俊浠":{"name":"肖俊浠","sex":"♂","No":"08"},
  "08":{"name":"肖俊浠","sex":"♂","No":"08"},
  "余炜浩":{"name":"余炜浩","sex":"♂","No":"09"},
  "09":{"name":"余炜浩","sex":"♂","No":"09"},
  "张晋":{"name":"张晋","sex":"♂","No":"10"},
  "10":{"name":"张晋","sex":"♂","No":"10"},
  "张景越":{"name":"张景越","sex":"♂","No":"11"},
  "11":{"name":"张景越","sex":"♂","No":"11"},
  "张楚昊":{"name":"张楚昊","sex":"♂","No":"12"},
  "12":{"name":"张楚昊","sex":"♂","No":"12"},
  "陈昊言":{"name":"陈昊言","sex":"♂","No":"13"},
  "13":{"name":"陈昊言","sex":"♂","No":"13"},
  "罗晨捷":{"name":"罗晨捷","sex":"♂","No":"14"},
  "14":{"name":"罗晨捷","sex":"♂","No":"14"},
  "周宏熹":{"name":"周宏熹","sex":"♂","No":"15"},
  "15":{"name":"周宏熹","sex":"♂","No":"15"}
  }
  alert("姓名:" + json[q].name + "\n性别:" + json[q].sex + "\n学号:" + json[q].No)
}
</script>
JSON 语法
JSON 简介
JSON 使用
JSON 语法是 JavaScript 语法的子集。

JSON 语法规则
JSON 语法是 JavaScript 对象表示法语法的子集。

数据在名称/值对中
数据由逗号分隔
花括号保存对象
方括号保存数组
JSON 名称/值对
JSON 数据的书写格式是：名称/值对。

名称/值对包括字段名称（在双引号中），后面写一个冒号，然后是值：

"firstName" : "John"
这很容易理解，等价于这条 JavaScript 语句：

firstName = "John"
JSON 值
JSON 值可以是：

数字（整数或浮点数）
字符串（在双引号中）
逻辑值（true 或 false）
数组（在方括号中）
对象（在花括号中）
null
JSON 对象
JSON 对象在花括号中书写：

对象可以包含多个名称/值对：

{ "firstName":"John" , "lastName":"Doe" }
这一点也容易理解，与这条 JavaScript 语句等价：

firstName = "John"
lastName = "Doe"
JSON 数组
JSON 数组在方括号中书写：

数组可包含多个对象：

{
"employees": [
{ "firstName":"John" , "lastName":"Doe" },
{ "firstName":"Anna" , "lastName":"Smith" },
{ "firstName":"Peter" , "lastName":"Jones" }
]
}
在上面的例子中，对象 "employees" 是包含三个对象的数组。每个对象代表一条关于某人（有姓和名）的记录。

JSON 使用 JavaScript 语法
因为 JSON 使用 JavaScript 语法，所以无需额外的软件就能处理 JavaScript 中的 JSON。

通过 JavaScript，您可以创建一个对象数组，并像这样进行赋值：

例子
var employees = [
{ "firstName":"Bill" , "lastName":"Gates" },
{ "firstName":"George" , "lastName":"Bush" },
{ "firstName":"Thomas" , "lastName": "Carter" }
];
可以像这样访问 JavaScript 对象数组中的第一项：

employees[0].lastName;
返回的内容是：

Gates
可以像这样修改数据：

employees[0].lastName = "Jobs";
亲自试一试
在下面的章节，您将学到如何把 JSON 文本转换为 JavaScript 对象
