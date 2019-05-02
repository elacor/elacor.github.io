# 欢迎使用中间语词典!/Welcome to Middle Language!
<html><head>
<script language="JavaScript">
function func()
{
var keyword=document.forms[0].keyword.value;//关键字
var r=document.body.createTextRange();
var s='<font style="background-color: #FFFF00;">'+keyword+'</font>';
while(r.findText(keyword)){
for(var o=r.parentElement();o&&o.tagName!="A";o=o.parentElement);
if(!o)try{
r.pasteHTML(s);
}catch(e){}
r.collapse(false);
}
return false;
}
</script>
</head><body>
<form onSubmit="return func();">
<input name='keyword' type='text' value="******">
<input type=submit value='Search'>
</form>
</body></html>
