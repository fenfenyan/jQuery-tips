# jQuery-tips
I am learning jQuery in my three-month internship
jQuery格式化  $.formatString
举例（用于表示函数的实参）
var a3 =  $.formatString('<li class="fa fa-trash" onclick="deletePwd(\'{0}\',\'{1}\');" title="删除密码"></li>',id,devicePwdList[i].id);
a3变成<li class="fa fa-trash" onclick="deletePwd('1','70');" title="删除密码"></li>，其中\'{0}\'和\'{1}\'分别代表了id和devicePwdList[i].id这两个值
jQuery eval函数
eval() 函数可计算某个字符串，并执行其中的的 JavaScript 代码，举例：
eval("x=10;y=20;document.write(x*y)")，输出200
