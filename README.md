<!-- VOLLEYBALL STATS-->
<html>
<head>
<title>Page Title</title>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}

table {
font-family: arial, sans-serif;
border-collapse: collapse;
width: 100%;
}

td, th {
border: 1px solid #F9F9F9;
text-align: left;
padding: 8px;
}

tr:nth-child(even) {
background-color: #F9F9F9;
}
.dropbtn {
background-color: #3498DB;
color: white;
padding: 16px;
font-size: 16px;
border: none;
cursor: pointer;
}

.dropbtn:hover, .dropbtn:focus {
background-color: #2980B9;
}

.dropdown {
position: relative;
display: inline-block;
}

.dropdown-content {
display: none;
position: absolute;
background-color: #f1f1f1;
min-width: 160px;
overflow: auto;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
}

.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}
</style>
</head>
<body>

<h2>Clickable Dropdown</h2>
<p>Click on the button to open the dropdown menu.</p>

<div class="dropdown">
<button onclick="myFunction()" class="dropbtn">Menu</button>
<div id="myDropdown" class="dropdown-content">
<a href="https://laurapellicano.github.io/game-stats//">Home</a>
<a href = "https://laurapellicano.github.io/volleyball-stats/?teamname=&coachname=&gamesanddates=/"> Statistics</a>
<a href="https://laurapellicano.github.io/Page2/">Page2</a>
<a href="https://laurapellicano.github.io/Page3/">Page3</a>
</div>
</div>

<script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
if (!event.target.matches('.dropbtn')) {

var dropdowns = document.getElementsByClassName("dropdown-content");
var i;
for (i = 0; i < dropdowns.length; i++) {
var openDropdown = dropdowns[i];
if (openDropdown.classList.contains('show')) {
openDropdown.classList.remove('show');
}
}
}
}

</script>

<h1 align="center">Volleyball Statistics</h1>
<img src="/Users/laura/Desktop/game-stats/volleyball.jpg" alt = "volleyball" width=200 align="right">
<h2>How to manage your teams statistics<h2>
<ol> 
<li>Create a team profile</li>
<li>Create a profile for each player on your team</li>
<li>Create a game profile for each game in your season</li>
<li>Within each game profile you will be able to upload each individuals players statistics for that specific game</li>
<li>After each game you are able to look at the team profile and each individual profile for more details and graphs for the season!</li>
</ol>

<p1>Team Profile</p1>
<div>
<table id= "table1" style="width:100%">
<tr>
<th>Team name</th>
<th>Coach</th> 
<th>Number of players </th>
<th>Games and dates </th>
</tr>
<br/><br/>
                            


<table border = "1" width = "100%"><tr>
<form action="mailto:someone@example.com" method="post" enctype="text/plain">
<thead>
<tr>
<td colspan = "4">Game Statistcs</td>
</tr>
</thead>
<tbody>
<tr>
<td><th><label for="Date"></label>Date:<br>
<input type="text" name="Date"><br>
<td><th><label for="Opponent "></label>Opponent:<br>
<input type="text" name="Opponent"><br>
<td><th><label for="Location"></label>Location:<br>
<input type="text" name="Location"><br>
<td><th><label for="Other"></label>Other:<br>
<input type="text" name="Other"><br>

<tfoot>
<tr>
<td colspan = "4"><table>
<th><label for="Name"></label>  Name:<br>
<input type="text" name="Name"><br>
<th><label for="Serve (In Play)"></label> Serve (In Play):<br>
<input type="text" name="Serve (In Play)"><br>
<th><label for="Serve (Ace)"></label> Serve (Ace):<br>
<input type="text" name="Serve (Ace)"><br>
<th><label for="Serve (Error)"></label>Serve (Error):<br>
<input type="text" name="Serve (Error)"><br>
<th><label for="Serve Receive "></label>Serve Receive:<br>
<input type="text" name="Serve Recieve"><br>
<th><label for="Assist"></label>Assist:<br>
<input type="text" name="Serve Recieve (Error)"><br>
<th><label for="Serve Recieve (Error)"></label>Serve Recieve (Error):<br>
<input type="text" name="Assist"><br>
<th><label for="Kill"></label>Kill:<br>
<input type="text" name="Kill"><br>
<th><label for="Offense (Error)"></label>Offense (Error):<br>
<input type="text" name="Offense (Error)"><br>
<th><label for="Dig"></label>Dig:<br>
<input type="text" name="Dig"><br>
<th><label for="Dig (Error)"></label>Dig (Error):<br>
<input type="text" name="Dig (Error)"><br>

<tr>
<td><input type="text" name="name"><br></td>
<td><input type="text" name="serveinplay"><br></td>
<td><input type="text" name="serveace"><br></td>
<td><input type="text" name="serveerror"><br></td>
<td><input type="text" name="servereceive"><br></td>
<td><input type="text" name="servereceiveerror"><br></td>
<td><input type="text" name="assist"><br></td>
<td><input type="text" name="kill"><br></td>
<td><input type="text" name="killerror"><br></td>
<td><input type="text" name="dig"><br></td>
<td><input type="text" name="digerror"><br></td>
</tr>
<tr>
<td><input type="text" name="name"><br></td>
<td><input type="text" name="serveinplay"><br></td>
<td><input type="text" name="serveace"><br></td>
<td><input type="text" name="serveerror"><br></td>
<td><input type="text" name="servereceive"><br></td>
<td><input type="text" name="servereceiveerror"><br></td>
<td><input type="text" name="assist"><br></td>
<td><input type="text" name="kill"><br></td>
<td><input type="text" name="killerror"><br></td>
<td><input type="text" name="dig"><br></td>
<td><input type="text" name="digerror"><br></td>
</tr>
<tr>
<td><input type="text" name="name"></td>
<td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>
 </tr>
 <tr>
 <td><input type="text" name="name"><br></td>
 <td><input type="text" name="serveinplay"><br></td>
 <td><input type="text" name="serveace"><br></td>
 <td><input type="text" name="serveerror"><br></td>
 <td><input type="text" name="servereceive"><br></td>
 <td><input type="text" name="servereceiveerror"><br></td>
 <td><input type="text" name="assist"><br></td>
 <td><input type="text" name="kill"><br></td>
 <td><input type="text" name="killerror"><br></td>
 <td><input type="text" name="dig"><br></td>
 <td><input type="text" name="digerror"><br></td>



<tfoot>
<tr>
<td colspan = "4"><div> 
<input type="submit" value="Send">
<input type="reset" value="Reset">
</div>
</td>
</tr>



                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
