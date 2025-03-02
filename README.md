# web-baitap
<html>
<head>
<title>2356210059-PHAM VAN THU THAU</title>

<script>
function tinhtong(x1,x2)
{
return parseInt(x1)+parseInt(x2);
}


function tinhhieu(x1,x2)
{
return parseInt(x1)-parseInt(x2);
}
 
function tinhtich(x1,x2)
{
return parseInt(x1)*parseInt(x2);
}

function tinhthuong(x1,x2)
{
return parseInt(x1)/parseInt(x2);
}


function tinhtongdayso(x1,x2)
{
var tong;
tong=0;
for ( let i=parseInt(x1);i<=parseInt(x2);i++)
tong=tong+i;
localStorage.x=tong;
return tong;
}

function thongbao()
{
for (let i=1;i<=10;i++)
alert(localStorage.x)
}






</script>
</head/>
<body>
<form>
<label> So thu 1:</label>
<input type="text' id="sothu1" name="sothu1">
<br><br>
<label> So thu 2:</label>
<input type="text' id="sothu2" name="sothu2">
<br><br>
<label> So thu 3:</label>
<input type="text' id="sothu3" name="sothu3">
<br><br>
<input type="button" onclick="sothu3.value=tinhtong(sothu1.value,sothu2.value)" value="Tinh tong">

<input type="button" onclick="sothu3.value=tinhhieu(sothu1.value,sothu2.value)" value="Tinh hieu">

<input type="button" onclick="sothu3.value=tinhtich(sothu1.value,sothu2.value)" value="Tinh tich">

<input type="button" onclick="sothu3.value=tinhthuong(sothu1.value,sothu2.value)" value="Tinh thuong">

<input type="button" onclick="sothu3.value=tinhtongdayso(sothu1.value,sothu2.value)" value="Tinh tong day so">

<input type="button" onclick="sothu3.value=thongbao()" value="Thong bao">


</form>
</body>
</html>
