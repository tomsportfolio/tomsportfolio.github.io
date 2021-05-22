
<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>
<title>Study Link Site</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="Javascript/scripty.js"></script>
<link href="https://fonts.googleapis.com/css?family=Staatliches" rel="stylesheet"> 




<link rel="stylesheet" type="text/css" href="Css/Sylesheet.css">

</head>
<body>

<script type="text/javascript">
function randomlinks1(){
    var myrandom=Math.round(Math.random()*1)
    var links=new Array()
    links[0]="https://shmeeb.itch.io/citation-needed"
    links[1]="https://www.bbc.co.uk/news/av/stories-51974040"
 
    window.location=links[myrandom]
}
</script>
<form>
<input type="button" value="Click here to go to either the game or the article." onClick="randomlinks1()">
</form>


<script type="text/javascript">
function randomlinks2(){
    var myrandom=Math.round(Math.random()*1)
    var links=new Array()
    links[0]="https://forms.office.com/r/94nXQt2cyA"
    links[1]="https://forms.office.com/r/mPsSaZm4Ms"
 
    window.location=links[myrandom]
}
</script>
<form>
<input type="button" value="Click here to return to the survey." onClick="randomlinks2()"()>
</form>

</body>
</html>