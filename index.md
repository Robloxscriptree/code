<html>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<div class=be>



<br id=hi>
<br id=hi>
<br>
<br>
<br>




<h2 id=h2>
1 sec, gotta finish pulling carrots
</h2>
<div class="float-container"  id=namo>

<h420 >Welcome To The Code </h420>
<h69 id=name>........</h69>
<br>
</div>
<br>

<h5 id=h5>

</h5>
<h3 id=h3>
he
</h3>
<h4 id=h4>

</h4>
<h6>
Have a good day!
</h6>

<div class=be>


<button type="button" class=button    id=hey>
Continue
</button>

</div>
</div>

<script type="text/javascript"  >
let x;
switch (new Date().getDay()) {

 case 0:
    x = "Sunday";
    break;
  case 1:
    x = "Monday";
    break;
  case 2:
    x = "Tuesday";
    break;
  case 3:
    x = "Wednesday";
    break;
  case 4:
    x = "Thursday";
    break;
  case 5:
    x = "Friday";
    break;
  case  6:
    x = "Saturday";
}


var today= new Date()
var time= today.getHours()+":"+ today.getMinutes()+":"+ today.getSeconds();


var curHr = today.getHours()

if (curHr < 12) {
  t=('Good Morning')
} else if (curHr < 18) {
  t=('Good Afternoon')
} else {
  t=('Good Evening')
}
document.getElementById("h3").innerHTML= "Today is: "+ x;

document.getElementById("h5").innerHTML= t;



function load(){
const username = prompt("What is your name?");
document.cookie = ""+username+"; SameSite=None; Secure";
const x=document.cookie;document.getElementById("name").innerHTML=x+" :)";
const re=setInterval(r,20);
function r (){
var today= new Date()
var time= today.getHours()+":"+ today.getMinutes()+":"+ today.getSeconds();
document.getElementById("h4").innerHTML= "The time is: "+time

};
setTimeout(function(){
$("h2").hide()

$("#namo").show()
$("#hey").show()},4000);



console.log("loaded")

}

window.onload=load;
$("#hey").click(function(){
setTimeout(function(){
$("#namo").hide();
$("h1").hide();
$("#hey").hide();
setTimeout(function(){

$("h4").show();
$("h3").show();
$("h5").show();
$("h6").show();
},1100)
},500)})



</script>
</html>
<style>
h1 {
  text-align:center;
  font-size:4em;
  display:none;
     background-color:black;
     color:white;
}
.be{
   
  background-color:black;

}
.center{
  
  background-color:black;
}
h2 {
  text-align:center;
  font-size:4em;
    background-color:black;
    color:orange
 
}
h3 {
  text-align:center;
  font-size:2em;
 display:none;
     background-color:black;
     color:white;
}
h4 {
  text-align:center;
  font-size:2em;
 display:none;
     background-color:black;
     color:white;
}
h5 {
  text-align:center;
  font-size:2em;
 display:none;
     background-color:black;
     color:green;
}
h6 {
  text-align:center;
  font-size:2em;
 display:none;
     background-color:black;
     color:green;
}

.button {
    text-align:center;
  display:none;
justify-content:center;
align-items:center;
  padding: 0;
  width: 100%;
  height: 10%;
  border: none;
  background-color: #04AA6D;
  color: white;
  padding: 14px 28px;
  font-size: 16px;
  cursor: pointer;
  
}
html{
  background-color:black;
  color:black;
}

#namo{
  text-align:center;
  color:white;
  font-size:4em;
  display:none;
}
#name{
  color:orange;
}
h420{
  
 color:green;
}
</style>

<script src="script.js"></script>
<script type="text/javascript"
