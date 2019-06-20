# job
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
<style>
.bg-1
{
background-color:blue;
color:white;
}

.bg-3
{

}

#back
{
margin-right:20%;
margin-left:65%;
margin-top:3px;

}
.vl {
  border-left: 1px solid white;
  height: 150px;
  position: absolute;
  left: 20%;
  margin-left: -3px;
  top: 40;
}
.v2{
  border-left: 1px solid white;
  height: 150px;
  position: absolute;
  left: 55%;
  margin-left: -3px;
  top: 40;
}

</style>
</head>
<body background="job5.png">

<div class="container-fluid bg-1">
  <div class="row">
<div class="col-sm-6 ">
  <h2>Employ.im</h2>
</div>
<div class="col-sm-6">
  <ul class="nav nav-tabs">
   
    <li><a data-toggle="tab" href="#menu1" style="color:black">find a job</a></li>
    <li><a data-toggle="tab" href="#menu2"style="color:black">candidates</a></li>
    <li><a data-toggle="tab" href="#menu3"style="color:black">employeee</a></li>
  </ul>
</div>
</div>

  <div class="tab-content">
    
    <div id="menu1" class="tab-pane fade">
      <h3>Menu 1</h3>
      <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <div id="menu2" class="tab-pane fade">
      <div class="row">
<div class="col-sm-4">

<h2>candidates</h2>
<p>Start applying instantly</p>

</div>
<div class="vl"></div>
<div class="col-sm-4">
<h2> get started</h2>
<p> job search</p>
<p> company search</p>
<p>create your cv</p>
<p>how it works</p>
</div>
<div class="v2"></div>
<div class="col-sm-4">
<h2>find a job today</h2>
<div class="row">
<button type="button" class="btn btn-default">login</button>
<br>
</div>
<br>
<div class="row">
<button type="button" class="btn btn-danger">register</button>
</div>
</div>
    </div>
</div>
    <div id="menu3" class="tab-pane fade">
      <h3>Menu 3</h3>
      <p>Eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.</p>
    </div>
  </div>
</div>

<div id="home" class="tab-pane fade in active">

      <h1>find your desrerved job</h1>

   	
<div id="back" style="background-color:white;width:400px ;height:300px">

  <h2>Form</h2>
  <form action="/action_page.php">
<div class="form-group">
      <div class="col-sm-9">
      <input type="name" class="form-control" id="name" style="color-#ccffff" placeholder="Enter name" name="name">
<br>
    </div>
<br>
</div>
    <div class="form-group">
      <div class="col-sm-9">
      <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
<br>
</div>
    </div>
    <div class="form-group">
      <div class="col-sm-9">
      <input type="company" class="form-control" id="company" placeholder="Company" name="company">
    </div>
</div>
    <div class="checkbox">
      <label><input type="checkbox" name="remember"> Remember me</label>
    </div>
<div class="col-sm-9">
    <button type="submit" class="btn btn-danger">find a job now</button>
</div>
  </form>
</div>

</body>
</html>




</body>
</html>
