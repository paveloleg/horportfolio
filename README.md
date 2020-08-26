
<!DOCTYPE html>
<html lang="ru">
<head>

  <meta charset="CP-1251">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>
  <style>
  body {
      position: relative;

  }
#section1{
  color:white;font-size:16pt;opacity:90%;background-image:url(office.jpg);padding-top:100px;padding-bottom:10px;
}
#section2{
  color:white;background-image:url(Bg.jpg);padding-top:99px;padding-bottom:320px;
}
#section3{
   color:white;padding-top:260px;padding-bottom:227px;
}
#section4{
  opacity: 50%;
  background-image: url("images/call.jpg");
}
  </style>
  <title>Horportfolio</title>
</head>

<body data-spy="scroll" data-target=".navbar" data-offset="50">

<nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top" style="padding-left:10px:"  >
  <ul class="navbar-nav" style="padding-right:10px;" >
    <li class=" nav-item">
      <a class="nav-link" href="#section1">Work</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#section2">About</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#section3">Blog</a> </li>
     <li class="nav-item">
      <a class="nav-link" href="#section4">Contact</a> </li>
     <li class="nav-item" style="">
<!-- Button to Open the Modal -->
<a class="text-white" data-toggle="modal" data-target="#myModal">
  HP
</a>
     </li>

  </ul>
</nav>
 <br />
  <br />
  <br />

<!-- The Modal -->
<div class="modal" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">

      <!-- Modal Header -->
      <div class="modal-header">
        <h4 class="modal-title">Authorization</h4>
        <button type="button" class="close" data-dismiss="modal">&times;</button>
      </div>

      <!-- Modal body -->
      <div class="modal-body">
<form class="form-inline" action="/action_page.php">
  <label for="email">Login:</label>
  <input type="email" class="form-control" id="email">
  <label for="pwd">Password:</label>
  <input type="password" class="form-control" id="pwd">
  <div class="form-check">
    <label class="form-check-label">
      <input class="form-check-input" type="checkbox"> Remember me
    </label>
  </div>
  <button type="submit" class="btn btn-primary">Enter</button>
</form>
      </div>

      <!-- Modal footer -->
      <div class="modal-footer">
        <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
      </div>

    </div>
  </div>
</div>


 <!--Work container-->
<div  id="section1" class="bg-light  text-justify container-fluid" ><br /><br />
  <h1 class="text-center text-justify">Work</h1>
  <h3 style="padding:10px;">Hello, there i am show you, while i haven't projects</h3>
  <p style="padding:10px;">1. The development of any site begins with the concept of: We need to figure out where, taking into account usability, place site navigation elements.
  <br />2. What menu items should be in the header, which font to choose, the main color of the link text and when you hover over it. Which background for the site to choose, just the background color or image. Where to place the main text relative to the background image.
  <br />3. Next, created a database for the blog., In which it was necessary to create entities with attributes id, description, title, date, author. Fill them with material (articles). With a cycle, remove them from the database in turn when you click on the Blog button.Also created an admin panel with the ability to add, edit and delete materials (articles) from the database.
  <br />4. When you press the Work button, all the data with the source codes of my work is displayed, what I worked on while I was in college, as well as additional work outside of the planned studies.
  <br />5. When you click on the Contacts button, a phone number, email, and my contacts are displayed in popular messengers. I also plan feedback with the chat bot.</p>

</div>
<div class="row">

<!--Card Web-->
<div class="container-fluid d-flex flex-row">
<!--Card Web-->
  <div class="card" style="width:600px">
    <img class="card-img-top" src="web.png" alt="Card image" style="width:100%">
    <div class="card-body">
      <h4 class="card-title">Web</h4>
      <p class="card-text">В данном разделе Вы найдете пример работ выполненые мною во время учебы.  </p>
      <a href="web.html" class="btn btn-primary">See more</a>
    </div>
  </div>

<!--Card Programming-->
    <div class="card" style="width:600px">
    <img class="card-img-top" src="prg.png" alt="Card image" style="width:100%">
    <div class="card-body">
      <h4 class="card-title">Programming</h4>
      <p class="card-text">В данном разделе находятся примеры кода на языках Python, C++</p>
      <a href="progr.html" class="btn btn-primary">See more</a>
    </div>
  </div>
</div>
  <br />
<div class="container-fluid d-flex flex-row">
 <!--Card Database-->
    <div class="card" style="width:600px">
    <img class="card-img-top" src="db.png" alt="Card image" style="width:100%">
    <div class="card-body">
      <h4 class="card-title">Database</h4>
      <p class="card-text">В данном разделе выложены примеры работ в Microsoft Access  и популярной базе данных MySql </p>
      <a href="#" class="btn btn-primary">See more</a>
    </div>
  </div>
<br/>
<!--Card Network.-->
  <div class="card" style="width:600px">
    <img class="card-img-top" src="network.png" alt="Card image" style="width:100%">
    <div class="card-body">
      <h4 class="card-title">Network</h4>
      <p class="card-text">В данном разделе находятся работы выполненные в программе Cisco.</p>
      <a href="#" class="btn btn-primary">See more</a>
    </div>
  </div>
<br><br/>
</div>
</div>

<!--Slideshow-->
<br/>
<div id="demo" class="carousel slide" data-ride="carousel">

  <!-- Indicators -->
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
  </ul>

 <!-- The slideshow -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="about.jpg" alt="About me" width="500" height="500">
    </div>
    <div class="carousel-item">
      <img src="work.jpg" alt="Chicago" width="500" height="500">
    </div>


  <!-- Left and right controls -->
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>
</div>


<br/>
<br/>


<!--About me container-->
<div id="section2" class="container-fluid bg-light text-center text-justify" >
 <br /> <br /> <br /><br />
  <h1>Front-End Developer</h1>
  <p class="card-text">
Hi, my name is Paul. I am a beginner front-end developer. In 2019, he went to study at Zaporizhzhya Aviation College. There, over two years of training, I learned how to work with databases in Microsoft Access, learned how to write programs in C ++. And also during non-academic time I study Python, PHP and the Codeigniter framework.
  </p>
  <p>But most of all I was interested in website development. This requires knowledge of HTML5, CSS3, Javascript, PHP + Codeigniter. Therefore, I began to search for information on these technologies. Studying them gradually and making timid steps, I began to succeed.</p>
</div>
<!--Blog container-->
<div id="section3" class="container-fluid bg-secondary">
  <h1>Blog</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
</div>

<!--Contact container-->
<div id="section4" class="container-fluid bg-white text-white" style="padding:8px;padding-top:210px;padding-bottom:12px;">
  
<!--Contact form-->
<form class="form form-fluid" method="post" name="connect" action="/action_page.php">

  <div class="col-md bg-white text-dark">
  <h1>Адрес</h1><p> Украина,г.Запорожье, ул. Леппика 4, кв 46.</p>
  <p>Phone: <span class="badge badge-secondary">+38(068)1031728</span></p>
  <p>Email: <span class="badge badge-secondary">pashok29@gmail.com</span></p>
  <p>Viber: <span class="badge badge-secondary">PavelOlegovich</span></p>
  
 
  <h1>Связь со мной</h1>
  <p>Для вопросов и для связи используйте форму ниже. Спасибо.</P>
    <div class="modal-body" style="padding:2px">

<label for="name" class="form" style="margin-left: 5px;">Имя</label>
  <input type="text" id="name" /><br />
<label for="email" class="form" >Email</label>
  <input type="email" id="email" label="Email"/><br />
<label for="name_company" class="form">Название компании</label>
  <input type="text" id="name_company"><br />
<label for="phone" class="form">Телефон</label>
  <input type="tel" id="phone" ><br />
  <textarea name="textarea" cols="20"></textarea><br />
<button type="submit" class="btn btn-primary container-fluid">Enter</button>
</form>
    </div>
</div>
<script>


$(document).ready(function(){
    $('[data-toggle="popover"]').popover();
});
</script>

</body>
</html>
