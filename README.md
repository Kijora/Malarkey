
<html>
		<head>
		<style> 
				#DRAGON{ 
				font-size:200%;
				color:White;
				text-align:center;
				
}
				#MALARKEY{
				text-align:center;}
			body{ background:purple;
}

//#5030b3

			img{
				width:30%;
				height:40%;
}
</style>
<script>
var Example_code = [2,3,1,2]
var Example2_code = [0,0,0,0]
function Test(clicked)
{
	Example2_code[0] = clicked	
	if ((Example2_code[0] == Example_code[0])&&(Example2_code[1] == Example_code[1])&&(Example2_code[2] == Example_code[2])&&(Example2_code[3] == Example_code[3])){
		alert("Well Done") 
		window.location = "TrueMalarkey.html"
		
	}
	Example2_code[3] = Example2_code[2]
	Example2_code[2] = Example2_code[1]
	Example2_code[1] = Example2_code[0]
}
function mk_msg(msg){
document.getElementById("msg-container").innerHTML = msg; }
</script>
		</head>
		<body>
				<div id="DRAGON">
				<p> Welcome to the Order of The Scortched Anvil of Malarkey!
</div>
		<div>
				

		<div>
				<div id="MALARKEY">
			<img src="https://cdn3.bigcommerce.com/s-nf2x4/images/stencil/500x659/products/246/1422/biz4__99043.1482504766.jpg?c=2" onclick="Test(1)"/>
			<img src="http://1.bp.blogspot.com/-Ndi-ngGShbk/UYf2Nabx_rI/AAAAAAAACMI/4v_Qh7PkeyA/s1600/giant+rubber+duck.jpg" onclick="Test(2)"/>
			<img src="https://amsterdamduckstore.com/wp-content/uploads/2016/06/Ninja-Rubber-Duck-Blue-front.jpg"onclick="Test(3)"/>	
</div>
<p id="msg-container"></p>
</body>
</html>
