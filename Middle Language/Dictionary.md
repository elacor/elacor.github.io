# 欢迎使用中间语词典!/Welcome to use the dictionary of Middle Language!
<input type="text" id="txt"/>
<input type="button" id="btn" value="查询/Search" onclick="go()"/>
<script>
function go(){
Document.write(sea($(#txt).val()))}
let sea=(text)=>{
var dic={
"ludi":"玩"}
return(dic[text])}
</script>
