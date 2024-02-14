# BindTimeCapsule
A a useful library of 5 asynchronous functions for using variables in extemporaneous parallel streams. It can be enriched
<html>
<head>
//need jquery
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
//call library
<script type="text/javascript" src="../bindTimeCapsule.JS"></script>
<head>
<body>
//example of usage with bindJ function with 5 param
 <script type="text/javascript">
		$(function () {
			$("#btnGet").click(function () {
					;(async () => {
					 const timeCapsule = await bindJ("Name", "POST", "api/AjaxAPI/AjaxMethod", "application/json; charset=utf-8", "json");
					   alert(timeCapsule.Name+" "+timeCapsule.DateTime);
					  })()
		  });
		});
</script>
</body>
</html>
