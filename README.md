# Chris-KuK.github.io
Homepage
https://codepen.io/Chris_Avenue/pen/mXPdBb



HTML:
<html>
  <head>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <title>KuK Crowdfunding Mockup</title>
  </head>
  <body>
    <nav class="navbar navbar-light bg-light justify-content-between">
  <a class="navbar-brand"><img src="https://chris-kuk.github.io/Logo+Name.png" width="120px"></img></a>
    <div>
    <button class="btn btn-outline-success my-2 my-sm-0 mx-1" type="button">Login</button>
    <button class="btn btn-outline-success my-2 my-sm-0 mx-1" type="button">Registrieren</button>
    </div>
</nav>
 <div class="container">
  <div class="jumbotron">
    <img id="teachpic" src="https://chris-kuk.github.io/Background_Frontpage.jpg"/>
    <h1>Bootstrap Tutorial</h1>      
    <p>Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile-first projects on the web.</p>
  </div>
</div>
  
 <div id="loginpopupbox"> 
<form name="login" action="" method="post" onsubmit="loginSubmit()">
<center>E-Mail:</center>
<center><input name="email" size="14" /></center>
<center>Passwort:</center>
<center><input name="password" type="password" size="14" /></center>
<center><input type="submit" name="submit" value="login" /></center>
</form> 
  </div>
   <div id="registerpopupbox"> 
     
<form name="register" action="" method="post" onsubmit="registerSubmit()">
<div id="registerleft">  
<ul id="registerlist">  
<li>Vorname:
  <input name="givenname" size="14" /></li>
<li>Nachname:
  <input name="surname" size="14"/></li>
<li>E-Mail:
  <input name="email" size="14"></li> 
<li>Passwort:
  <input name="password" type="password" size="14" /></li>
<li>Passwort:
  <input name="passwordcheck" type="password" size="14" /></li>
  <li><input type="checkbox" size="14" name="teacher" /> ich bin Lehrer/in</li>
  <li><input type="submit" name="submit" value="register" /></li>
  </ul>  
  </div>
  <div id="registerright"><p>Profilbild</p><input type="file" name="profilepic" id="profilepic"></input></div>
</form> 
  </div>
 <div id="therest"></div>
 </body>


</html>



<div class="form-style-10">
<h1>Investiere jetzt!<span>Melde dich and und unterstütze Schulprojekte in Österreich </span></h1>
<form>
    
    <div class="inner-wrap">
        <label>Vorname <input type="text" name="field1" /></label>
        <label>Nachname <textarea name="field2"></textarea></label>
       <label>E-mail Adresse <input type="email" name="field3" /></label>
        <label>Telefonnummer <input type="text" name="field4" /></label>
      
        <label>Passwort <input type="password" name="field5" /></label>
        <label>Passwort bestätigen <input type="password" name="field6" /></label>
    </div>

  

  
    <div class="button-section">
     <input type="submit" name="Sign Up" />
     <span class="privacy-policy">
     <input type="checkbox" name="field7">Hiermit bestätige ich, dass ich eine ausgebildete Lehrperson bin und an einer österreichischen Schule unterrichte.
     </span>
    </div>
</form>
</div>


-------------------
CSS:
#menuline{
  padding-left: 9em;
}

#logo{
  background: url(https://freelogo-assets.s3.amazonaws.com/assets/images/logos/gif/fls-logo_042.gif) no-repeat;
}  

.mainmenu{
  border: none;
  background: transparent;
}

#loginpopupbox{
  visibility: hidden;
}

#registerpopupbox{}

#registerleft{
  float: left;
  padding-left: 9em;
}

#registerright{
  float: right;
  padding-right: 12em;
}

#teachpic{
  width: 70vw;
  height: 100vh;
  padding-left: 9em;
  margin-left: 2px;
  filter:alpha(opacity=70); -moz-opacity: 0.70; opacity: 0.70;
}

#registerlist{
  list-style-type: none;
  
}

#registerpopupbox{
     width:450px;
    padding:30px;
    margin:40px auto;
    background: #FFF;
    border-radius: 10px;
    -webkit-border-radius:10px;
    -moz-border-radius: 10px;
    box-shadow: 5px 5px 10px rgba(5, 5, 5, 0.13);
    -moz-box-shadow: 5px 5px 10px rgba(5, 5, 5, 0.13);
    -webkit-box-shadow: 5px 5px 10px rgba(5, 5, 5, 0.13);
}


<link href='http://fonts.googleapis.com/css?family=Bitter' rel='stylesheet' type='text/css'>
<style type="text/css">
.form-style-10{
    width:450px;
    padding:30px;
    margin:40px auto;
    background: #FFF;
    border-radius: 10px;
    -webkit-border-radius:10px;
    -moz-border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.13);
    -moz-box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.13);
    -webkit-box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.13);
}
.form-style-10 .inner-wrap{
    padding: 30px;
    background: #F8F8F8;
    border-radius: 6px;
    margin-bottom: 15px;
}
.form-style-10 h1{
    background: #2A88AD;
    padding: 20px 30px 15px 30px;
    margin: -30px -30px 30px -30px;
    border-radius: 10px 10px 0 0;
    -webkit-border-radius: 10px 10px 0 0;
    -moz-border-radius: 10px 10px 0 0;
    color: #fff;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.12);
    font: normal 30px 'Bitter', serif;
    -moz-box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.17);
    -webkit-box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.17);
    box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.17);
    border: 1px solid #257C9E;
}
.form-style-10 h1 > span{
    display: block;
    margin-top: 2px;
    font: 13px Arial, Helvetica, sans-serif;
}
.form-style-10 label{
    display: block;
    font: 13px Arial, Helvetica, sans-serif;
    color: #888;
    margin-bottom: 15px;
}
.form-style-10 input[type="text"],
.form-style-10 input[type="date"],
.form-style-10 input[type="datetime"],
.form-style-10 input[type="email"],
.form-style-10 input[type="number"],
.form-style-10 input[type="search"],
.form-style-10 input[type="time"],
.form-style-10 input[type="url"],
.form-style-10 input[type="password"],
.form-style-10 textarea,
.form-style-10 select {
    display: block;
    box-sizing: border-box;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    width: 100%;
    padding: 8px;
    border-radius: 6px;
    -webkit-border-radius:6px;
    -moz-border-radius:6px;
    border: 2px solid #fff;
    box-shadow: inset 0px 1px 1px rgba(0, 0, 0, 0.33);
    -moz-box-shadow: inset 0px 1px 1px rgba(0, 0, 0, 0.33);
    -webkit-box-shadow: inset 0px 1px 1px rgba(0, 0, 0, 0.33);
}

.form-style-10 .section{
    font: normal 20px 'Bitter', serif;
    color: #2A88AD;
    margin-bottom: 5px;
}
.form-style-10 .section span {
    background: #2A88AD;
    padding: 5px 10px 5px 10px;
    position: absolute;
    border-radius: 50%;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border: 4px solid #fff;
    font-size: 14px;
    margin-left: -45px;
    color: #fff;
    margin-top: -3px;
}
.form-style-10 input[type="button"], 
.form-style-10 input[type="submit"]{
    background: #2A88AD;
    padding: 8px 20px 8px 20px;
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    color: #fff;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.12);
    font: normal 30px 'Bitter', serif;
    -moz-box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.17);
    -webkit-box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.17);
    box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.17);
    border: 1px solid #257C9E;
    font-size: 15px;
}
.form-style-10 input[type="button"]:hover, 
.form-style-10 input[type="submit"]:hover{
    background: #2A6881;
    -moz-box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.28);
    -webkit-box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.28);
    box-shadow: inset 0px 2px 2px 0px rgba(255, 255, 255, 0.28);
}
.form-style-10 .privacy-policy{
    float: right;
    width: 250px;
    font: 12px Arial, Helvetica, sans-serif;
    color: #4D4D4D;
    margin-top: 10px;
    text-align: right;
}
</style>

