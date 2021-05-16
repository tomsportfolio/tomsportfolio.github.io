
<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>
<title>Study Link Site</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="Javascript/scripty.js"></script>
<link href="https://fonts.googleapis.com/css?family=Staatliches" rel="stylesheet"> 

<script type="text/javascript">
function randomlinks(){
    var myrandom=Math.round(Math.random()*9)
    var links=new Array()
    links[0]="http://www.javascriptkit.com"
    links[1]="http://www.dynamicdrive.com"
    links[2]="http://www.cssdrive.com"
    links[3]="http://www.codingforums.com"
    links[4]="http://www.news.com"
    links[5]="http://www.gamespot.com"
    links[6]="http://www.msnbc.com"
    links[7]="http://www.cnn.com"
    links[8]="http://news.bbc.co.uk"
    links[9]="http://www.news.com.au"
 
    window.location=links[myrandom]
}
</script>
<form>
<input type="button" value="random link!" onClick="randomlinks()">
</form>


<link rel="stylesheet" type="text/css" href="Css/Sylesheet.css">

</head>
<body>

<div id ="Headbar">
	<UL>
		
		<li>
		
		<a href="https://www.youtube.com">Click Here</a>
		
		</li>
		
	</UL>
	
</div>

</body>
</html>