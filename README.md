<!DOCTYPE html>
<html>
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
  <style>
  body {
      position: relative; 
  }
  #section1 {padding-top:50px;color: black; background-color: #FFFFFF;}
  #section2 {padding-top:50px;color: black; background-color: #FFFFFF;}
  #section3 {padding-top:50px;color: black; background-color: #FFFFFF;}
  #section4 {padding-top:50px;color: black; background-color: #FFFFFF;}
  #section5 {padding-top:50px;color: black; background-color: #FFFFFF;}
  
  * {
  box-sizing: border-box;
}

/* Style inputs */
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}


/* Create two columns that float next to eachother */
.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
  </style>
</head>
<body data-spy="scroll" data-target=".navbar" data-offset="50">


  <!--<div class="container-fluid">
   <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">Radha Mahalingam</a>
    </div>
	<h2>Radha Mahalingam</h2>
    </div>-->
   
<nav class="navbar navbar-inverse navbar-fixed-top">
	<div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li><a href="#section1">About Me</a></li>
          <li><a href="#section2">Twitter Feed</a></li>
          <li><a href="#section3">Points of View</a></li>
		  <li><a href="#section4">Assignment Example</a></li>
		  <li><a href="#section5">Contact</a></li>
          <!--<li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Section 4 <span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="#section41">Section 4-1</a></li>
              <li><a href="#section42">Section 4-2</a></li>
            </ul>
          </li>-->
        </ul>
      </div>
    </div>
 
</nav>
<div class="container">

<div id="section1" class="container-fluid">
  
  <div class="col-md-10" style="padding:0">
	<h1>About Me</h1>
	<p>Senior Information Technology Executive and Client Partner with significant leadership, sales, delivery & consulting experience and demonstrated success in the Information Technology and Services industry. Thought leader in the Financial Services Industry (insurance, banking, financial markets) and latest technologies. Focused on bringing creative solutions involving products/platforms to complex client problems using ground breaking technologies and methods (Design Thinking, Cloud, Agile, Dev Ops, Blockchain, Data Analytics, Big Data, Machine Learning and AI)</p>
    <p>Delivered sustained positive business outcome to clients, leveraging expertise in Digital Transformation, Innovations Center Setup, IT Strategy & Process Improvement, Cloud Application Development, Migration & Modernization, Data Analytics, and Complex Transformation Program Management.</p>
  </div>
  <div class="col-md-2" style="padding:0">
	<img src="RM.png" class="rounded-circle" alt="Radha">
  </div>
  </div>
<div id="section2" class="container-fluid">
  <h1>Twitter Feed</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
</div>
<div id="section3" class="container-fluid">
  <h1>Points of View</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
</div>
<div id="section4" class="container-fluid">
  <h1>Assignment Example</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
</div>
<div id="section5" class="container-fluid">
  <h1>Contact</h1>
   
  <div class="row">
    
    <div class="column">
      <form action="/action_page.php">
        <label for="fname">First Name</label>
        <input type="text" id="fname" name="firstname" placeholder="Your name..">
        <label for="lname">Last Name</label>
        <input type="text" id="lname" name="lastname" placeholder="Your last name..">
		<div class="form-group">
			<label for="email">Email address:</label>
			<input type="email" class="form-control" id="email">
		 </div>
        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:170px"></textarea>
        <input type="submit" value="Submit">
      </form>
    </div>
  </div>
</div>
</div>
</body>
</html>
