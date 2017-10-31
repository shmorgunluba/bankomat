<html>
<head>
<script>      
document.getElementById('cancel').onclick = backspace(){
ans.value = ans.value.substring(0, ans.value.length - 1);
    }
</script>   
<title>
Банкомат
</title>
</head>
<body 
bgcolor= "# 000000" 
text= "gold"><form name="calculator" >
<form action="handler.php">
<input type="button" value="1" onClick="document.calculator.ans.value+='1'">
<input type="button" value="2" onClick="document.calculator.ans.value+='2'">
<input type="button" value="3" onClick="document.calculator.ans.value+='3'">
<input type="button" value="Cancel"   onClick="backspace()">
<br>
<input type="button" value="4" onClick="document.calculator.ans.value+='4'">
<input type="button" value="5" onClick="document.calculator.ans.value+='5'">
<input type="button" value="6" onClick="document.calculator.ans.value+='6'">
<input type="reset" value="CLEAR" ><br>
<input type="button" value="7" onClick="document.calculator.ans.value+='7'">
<input type="button" value="8" onClick="document.calculator.ans.value+='8'">
<input type="button" value="9" onClick="document.calculator.ans.value+='9'">
<br>
<input type="button" value="  " >
<input type="button" value="0" onClick="document.calculator.ans.value+='0'">
<input type="button" value="  " >
<input type="button" value="        "><br>
PIN  <input type="text" name="ans" id = "backspace" value=""/>
</form>
</body>
</html>
