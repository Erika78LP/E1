# E1<!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body></body>
    <style>
        .sidebar {
  margin: 0;
  padding: 0;
  width: 767px;
  background-color: #f1f1f1;
  position: fixed;
  height: 100%;
  overflow: left;
  dispaly: none;
}
  .container{
    background-color: grey;
    overflow: right;
    text-align: center;
    
  }
        .sidebar a:hover:not(.active) {
  background-color: #555;
  color: white;
    }
    
    .sidebar a {float: left;}
  div.content {margin-left: 0;}
}
    </style>
 <div class="sidebar">
  <ul>
    <li>
  <a class="active" href="#home">Home</a>
    </li>
  <li>
    <a href="#news">News</a>
    </li>
  <li><a href="#contact">Contact</a>
    </li>
    <li><a href="#about">About</a></li>
    <aside>
   <div class="container">
        <h1>Example headline.
        </h1>
        <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec is elit non mi porta gravida at eget <br> metus. Nullam id dolor id nibh ultricies ut id elit.</p>
        <a href="#" class="btn btn-lg btn-primary">
          Sign up today
        </a>
    </div>
  </aside>
</div>
</html>   
