# hello-world
Ideas and fun coding stuff!
Hello World! I am a full-stack web developer looking to share ideas and create some fun and usefull code.

2/6/19 LOG:
Just exploring GIT. Found a few links that would help with some development and programming >> 
Javascript: https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comment-your-javascript-code


HTML i made:
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.1/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Roboto+Slab" rel="stylesheet">
</head>
  <header>
  </header>
  <main>
    <div class="flex">
      <div class="2">
        <i class="fas fa-code fa-3x"></i>
      </div>
      <div id="back">
       <h2>&nbsp;&nbsp; Jordan Kramer &nbsp;&nbsp;</h2>
      </div>
    </div>
  </main>
  <body>
    <ul>
      <li>
        <i class="fab fa-cloudscale fa-8x"></i><h1>PBLMSLVNG</h1>
      </li>
       <li>
       <i class="fab fa-angrycreative fa-9x"></i><h1>CRTVTY</h1>
      </li>
       <li>
         <i class="fab fa-github fa-9x"></i><h1>GIT</h1>
      </li>

    </ul>

    
    
  </body>
  
  <footer>
    <div>
    <h2 id="footercolor">Jordan Kramer</h2>
      <p><a href="www.apple.com">Apple.com</p>
    </div>
    
    
    
  </footer>
</html>

CSS i made:

*{
  padding: 0px;
  margin: 0px;
}

header{
  background-color: red;
}
.fa-code{
  color: white;
}
.flex{
  display: flex;
  align-items: center;
  justify-content:center;
  background-color:purple;
  padding: 50px;
}
h2 {
  font-family: 'Roboto', sans-serif;
  color: white;
  line-height: 2em;
  cursor: pointer;
}
#back {
  padding: 0px;
  background-color:orange;
  margin-left: 15px;
  border-radius: 6px;
  box-shadow: 2px 2px white;
}
body {
  background-color: white;
}
.fab, .fas{
  padding: 5px;
}
.fa-cloudscale{
  color: green;
  opacity: .9;
  width: 80%;
  margin: auto;
  padding: 15px;
}
.fa-angrycreative {
  color: darkred;
}
.fa-github {
  color: #5D3F6A;
}
ul {
  display: flex;
  justify-content:center;
  flex-wrap: wrap;
  padding: 20px;
}
li {
  text-align: center;  
  list-style-type: none;
  padding: 20px;
}

li h1 {
  color: gray;
  font-size: 1.5em;
  font-family: 'Roboto Slab', serif;  
}

#footercolor {
  color: black;
  cursor: none;
}
