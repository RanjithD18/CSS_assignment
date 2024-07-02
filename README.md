## Assignment 2

### home.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Assignment</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      margin-top: 50px;
      margin-left: 50px;
      margin-right: 50px;
      border-radius: 0;
    }
    #text_c {
      background-color: #b0b0b0;
    }
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
    }
    body{
      background-image: url('back_g.jpg');
      background-size: cover;
      background-position: center;
      min-height: 100vh;
      height: 90%;
    }
    .align-center {
      padding-top: 10%;
      min-height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container-fluid justify-content-center">
      <a class="navbar-brand fs-2" href="#">ZORO</a>
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="product.html">Product</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="people.html">People</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
      <form class="d-flex">
        <input type="text"  id="text_c" class="form-control" placeholder="Type something...">
        <button type="submit" class="btn btn-primary">Submit</button>
      </input>
      </form>
      
    </div>
  </nav>

<div class="jumbotron text-center container-fluid align-center">
  <div class="container">
    <h1>"Driving progress through <br>precision engineering and<br>
      boundless creativity."
    </h1>      
    <div class="container">
      <button type="submit" class="btn btn-primary">Log in</button>
      <button type="submit" class="btn btn-primary">Sign Up</button>
    </div>
  </div>
</div>
  

<footer class="footer fixed-bottom bg-light text-center">
  <b>Designed and Developed By Ranjith D(212221240044)</b>
</footer>

</body>
</html>
~~~
### product.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      margin-top: 50px;
      margin-left: 50px;
      margin-right: 50px;
      border-radius: 0;
    }
    #text_c {
      background-color: #b0b0b0;
    }
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
    }
    body{
      background-image: url('back_g.jpg');
      background-size: cover;
      background-position: center;
      min-height: 100vh;
      height: 90%;
    }
    .align-center {
      padding-top: 10%;
      min-height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container-fluid justify-content-center">
      <a class="navbar-brand fs-2" href="#">ZORO</a>
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="product.html">Product</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="people.html">People</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
      <form class="d-flex">
        <input type="text"  id="text_c" class="form-control" placeholder="Type something...">
        <button type="submit" class="btn btn-primary">Submit</button>
      </input>
      </form>
      
    </div>
  </nav>

  <div class="container text-center align-center" style="padding-left: 10%;">
  <div class="row gx-3 gy-3">
    <div class="col-md-3 border border-white rounded text-white m-3">
      <h1 class="text-primary"><strong>C++</strong></h1><br>
      <p>Efficiency Redefined:<br>Harnessing the Power of C++<br>for Next-Level Development</p>
    </div>
    <div class="col-md-3 border border-white rounded text-white m-3">
        <h1 class="text-primary"><strong>JAVASCRIPT</strong></h1><br>
        <p>Scripting Success: Unleashing <br>the Power of Javascript.</p>
      </div>
    <div class="col-md-3 border border-white rounded text-white m-3">
        <h1 class="text-primary"><strong>PHP</strong></h1><br>
        <p>PHP is a server side scripting<br>language that is embedded in <br>HTML.</p>
    </div>
    <div class="col-md-3 border border-white rounded text-white m-3">
        <h1 class="text-primary"><strong>PYTHON</strong></h1><br>
        <p>Unlocking Innovation: Python<br>Paving the Way too Progress.</p>
    </div>
    <div class="col-md-3 border border-white rounded text-white m-3">
        <h1 class="text-primary"><strong>SQL</strong></h1><br>
        <p>SQL is a standard language<br>for accessing and<br>manipulating databases.</p>
    </div>
    <div class="col-md-3 border border-white rounded text-white m-3">
        <h1 class="text-primary"><strong>SHELL</strong></h1><br>
        <p>Shell can be accessed by<br> users using a command line <br>interface.</p>
    </div>
  </div>
</div>

  

<footer class="footer fixed-bottom bg-light text-center">
  <b>Designed and Developed By Ranjith D(212221240044)</b>
</footer>

</body>
</html>
~~~
### people.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      margin-top: 50px;
      margin-left: 50px;
      margin-right: 50px;
      border-radius: 0;
    }
    #text_c {
      background-color: #b0b0b0;
    }
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
    }
    body{
      background-image: url('back_g.jpg');
      background-size: cover;
      background-position: center;
      min-height: 100vh;
      height: 90%;
    }
    .align-center {
      padding-top: 10%;
      min-height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .people-card {
      margin-bottom: 30px;
    }
    .rounded-circle {
      width: 150px;
      height: 150px;
      object-fit: cover;
    }
    .people-card p {
      margin-bottom: 0;
    }
    
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container-fluid justify-content-center">
      <a class="navbar-brand fs-2" href="#">ZORO</a>
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="product.html">Product</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="people.html">People</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
      <form class="d-flex">
        <input type="text"  id="text_c" class="form-control" placeholder="Type something...">
        <button type="submit" class="btn btn-primary">Submit</button>
      </input>
      </form>
      
    </div>
  </nav>

  <div class="container text-center mt-5" style="padding-top: 5%;">
    <div class="row gx-5 gy-5">
      <div class="col-md-4 people-card">
        <img src="1.jpg" alt="Person Name" class="rounded-circle mb-3">
        <h5 class="text-primary">John Doe</h5>
        <p class="text-white">ChairMan</p>
      </div>
      <div class="col-md-4 people-card">
        <img src="2.jpg" alt="Person Name" class="rounded-circle mb-3">
        <h5 class="text-primary">Jane Smith</h5>
        <p class="text-white">CEO</p>
      </div>
      <div class="col-md-4 people-card">
        <img src="3.jpg" alt="Person Name" class="rounded-circle mb-3">
        <h5 class="text-primary">Mike Johnson</h5>
        <p class="text-white">CTO</p>
      </div>
      <div class="col-md-4 people-card">
        <img src="4.jpg" alt="Person Name" class="rounded-circle mb-3">
        <h5 class="text-primary">Emily Davis</h5>
        <p class="text-white">Keyboardist</p>
      </div>
      <div class="col-md-4 people-card">
        <img src="5.jpg" alt="Person Name" class="rounded-circle mb-3">
        <h5 class="text-primary">Chris Brown</h5>
        <p class="text-white">Director</p>
      </div>
      <div class="col-md-4 people-card">
        <img src="6.jpg" alt="Person Name" class="rounded-circle mb-3">
        <h5 class="text-primary">Lisa White</h5>
        <p class="text-white">Asst. Director</p>
      </div>
    </div>
  </div>

  

<footer class="footer fixed-bottom bg-light text-center">
  <b>Designed and Developed By Ranjith D(212221240044)</b>
</footer>

</body>
</html>
~~~
### contact.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      margin-top: 50px;
      margin-left: 50px;
      margin-right: 50px;
      border-radius: 0;
    }
    #text_c {
      background-color: #b0b0b0;
    }
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
    }
    body{
      background-image: url('back_g.jpg');
      background-size: cover;
      background-position: center;
      min-height: 100vh;
      height: 90%;
    }
    .align-center {
      padding-top: 10%;
      min-height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .people-card {
      margin-bottom: 30px;
    }
    .rounded-circle {
      width: 150px;
      height: 150px;
      object-fit: cover;
    }
    .people-card p {
      margin-bottom: 0;
    }
    
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container-fluid justify-content-center">
      <a class="navbar-brand fs-2" href="#">ZORO</a>
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="product.html">Product</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="people.html">People</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
      <form class="d-flex">
        <input type="text"  id="text_c" class="form-control" placeholder="Type something...">
        <button type="submit" class="btn btn-primary">Submit</button>
      </input>
      </form>
      
    </div>
  </nav>

  <div class="container">
    <h2 class="text-center text-white">Contact Us</h2>
    
    <div class="row">
      <div class="col-md-6 form-container text-white">
        <h3>Contact Form</h3>
        <form>
          <div class="mb-3 text-white">
            <label for="name" class="form-label">Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="mb-3 text-white">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="mb-3 text-white">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      
      <div class="col-md-6 location-container text-white">
        <h3 >Our Location</h3>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6292.324242740333!2d80.01360705214385!3d13.025787946265357!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a52605c8001b0b3%3A0x17397b086e047e7c!2sSaveetha%20Engineering%20College!5e0!3m2!1sen!2sin!4v1719941687608!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </div>
  </div>

  

<footer class="footer fixed-bottom bg-light text-center">
  <b>Designed and Developed By Ranjith D(212221240044)</b>
</footer>

</body>
</html>
~~~
### Output:
![image](https://github.com/RanjithD18/CSS_assignment/assets/93427221/5c3438ce-d571-4302-ba4d-9f023dbf8f8d)
![image](https://github.com/RanjithD18/CSS_assignment/assets/93427221/1bb64788-691e-4e81-8a05-fc45c261c955)
![image](https://github.com/RanjithD18/CSS_assignment/assets/93427221/306cefa2-d62f-4a81-9f77-dd5fd99a7b8d)
![image](https://github.com/RanjithD18/CSS_assignment/assets/93427221/f53c0b51-835c-44ce-9012-dd0e8f4dc8b5)


