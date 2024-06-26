
<HTML>
<head>
<Title> About Software Engineering
</Title>
<body style="background-color:#7FF7A0;">
<h2> Software Engineering</h2>


</body>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

.tab {
overflow:hidden;
border: 1px solid #43AB4F;
background-color: #099429;
}

.tab button {
background-color: inherit;
float: left;
border: none;
outline: none;
cursor: pointer;
padding: 14px 16px;
transition: 0.3s;
font-size: 17px
}

.tab button:hover { background-color: #82DB7E;
}


.tab button.active { background-color: #59DE9A;
}

.tabcontent {
display: none;
padding: 6px 12px;
border: 1px solid #0EDE69;
border-top: none;

.topright {
float: right;
cursor: pointer;
font-size: 28px;
}

.topright:hover {color: red;}
</style>
</head>
<body>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Home')" id="defaultOpen">Home</button>
  <button class="tablinks" onclick="openCity(event, 'About')">About</button>
  <button class="tablinks" onclick="openCity(event, 'Contact')">Contact</button>
</div>


<div id="Home" class="tabcontent">
  <h2>Introduction to Software Engineering</h2>
  <p>About Software Engineering: The true heroes of the digital sector are software engineers. Our devices may transcend their plastic and silicon exteriors to become the invaluable tools we use today thanks to their skills and, of course, the wonders of modern engineering. From afar, the work that these coders do can appear intimidating, if not unintelligible. However, with the proliferation of computer science education and training opportunities, entering the software engineering field has never been easier even for those with little to no prior industry experience. It only needs a healthy amount of ambition, hard effort, vision, and adaptability to succeed. </p>
<h3>Steps to becoming a software engineer:</h3>
<ol>Make a Career Path</ol>
<ol>Obtain an Education</ol>
<ol>Experience</ol>
<ol>Earn a certificate</ol>
<ol>Apply for Jobs</ol>

<img src="cloud.png" width="200" height="120"/>
<img src="software.png" width="200" height="120"/>
<img src="keyboard.png" width="200" height="120"/>
<img src="words.png" width="200" height="120"/>

</div>

<div id="About" class="tabcontent">  
<h2>About Software Engineering:</h2>
<img src="gear.png" width="250" height="130"/> <img src="happyguy.png" width="250" height="130"/>


  <p>Software engineering usually means the creation and application of computer software and utility programs. Software engineers apply their extensive understanding of math to create software that meets the digital needs of users. Web developers, on the other hand, are primarily concerned with the development of websites. Everything from design and functionality to navigation and overall usability is the responsibility of these people.

You can begin navigating your academic and professional career route when you have a clear sense of what you want to do. </p>
 
<h3>Salary:</h3>
<p>The compensation of a software engineer varies depending on status and years of professional experience. And the difference in margins between countries can be shockingly large. For example, an entry-level software developer pay in the U. S. is $103,382, while it is $87,668 in Switzerland and $62,668 in Germany.</p>
<table border="1">
  <tr>
   
    <th>Monthly Salary:</th>
    <th>Yearly Salary:</th>
  </tr>
  <tr>
    <td>$68,000</td>
    <td>$103,382</td>
   </tr>    
</table>
<img style="display:block; margin-left auto; margin-right auto"src="salary2.png"width="30%"height="50%"/>
<img style="display:block; margin-left auto; margin-right auto"src="bars.png"width="30%"height="50%"/>

</div>

<div id="Contact" class="tabcontent">
  <h2>More Information:</h2>
  <img src="contact.png" width="200" height="120"/>
  <img src="contact2.png" width="200" height="120"/>

  <p>For more information about software engineering enter your contact information below</p>
 
 
  <form action="http://www.WebsiteDevelopmentBook.com/FormEcho.php" method="post">

Were you satisfied with this infomation?:
Yes <input type="radio" name="satisfied" value="yes"/>
No <input type="radio" name="satisfied" value="no"/>
  <form action="http://www.WebsiteDevelopmentBook.com/FormEcho.php"


method="post"><fieldset>
Name: <input type="input" name="username"/>
<br/><br/>
E-Mail: <input type="input" name="e-mail"/>
</fieldset>
<fieldset>
Gender: <select name=“Gender”>
<option>Male</option>
<option>Female</option>
<option>Other</option>

   
</select>
<br/><br/>
Contact Time EST: <select name=“time”>
<option>9:00AM</option>
<option>10:00AM</option>
<option>11:00AM</option>
<option>12:00PM</option>
<option>1:00PM</option>
<option>2:00PM</option>
<option>3:00PM</option>
<option>4:00PM</option>
<option>5:00PM</option>
</fieldset>

 

   
<input type="submit" value="Click to Submit"/>


<a href="https://www.coursera.org/articles/software-engineer">1st Reference</a>
<a href="https://www.daxx.com/blog/development-trends/it-salaries-software-developer-trends">2nd Reference</a>

</select>
</fieldset>
<br/>

</form>
</div>


<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

</script>



</body>
</html>
