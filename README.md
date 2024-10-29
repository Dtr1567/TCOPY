<!DOCTYPE html>
<html lang="en">
  <head>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="At SweetRBX.com you can easily earn hundreds of ROBUX for free, by completing very easy tasks.">
    <meta name="author" content="Python">
  
    <meta property="og:title" content="SweetRBX - Earn free ROBUX for completing easy quizzes, apps, and more!">
    <meta property="og:description" content="Earn Robux by completing quizzes, downloading games on your mobile device and watching videos!">
    <meta property="og:url" content="https://sweetrbx.com">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <link rel = "stylesheet" href="./css/login.css">
    <link rel =  "stylesheet" href="./css/header.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400&display=swap" rel="stylesheet">
    
     <link rel="stylesheet"href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css">
    <script src="https://kit.fontawesome.com/2d7a97658d.js" crossorigin="anonymous"></script>
    <link rel="icon" type="image/png" href="./img/favicon.png">

    <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-167834764-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-167834764-1');
</script>


    <title>SweetRBX - Earn Free Robux!</title>
  </head>
  <body>
                      
  <div class = "logo-big">
      <img src = "./img/login/sweetrbxlogo2.png" class = "logo-img">
      <a href = "#login" class = "join-link animate__animated animate__bounce animate__infinite	infinite">JOIN US!</a>
  </div>
    
   <div class = "parent">
       <div class = "about-us-box">

             
           <a href="#" class="btn btn-primary btn-lg disabled panel panel-1" tabindex="-1" role="button" aria-disabled="true">
                <span class="panel-txt">
                Login with <b>just</b> your
                <b>RBLX</b> Username! 
                <br></span>
                <img src = "./img/login/login-icon.png" class = "icon-img">
           </a>
             
           <a href="#" class="btn btn-primary btn-lg disabled panel panel-2" tabindex="-1" role="button" aria-disabled="true">
                <span class="panel-txt"> 
                   Complete <b>quick</b> and 
                   <b>easy</b> surveys, 
                   for <b>RBX!</b>
                    <br>
                </span>
                <img src = "./img/login/survey-icon.png" class = "icon-img">
        </a>
             
           <a href="#" class="btn btn-primary btn-lg disabled panel panel-3" tabindex="-1" role="button" aria-disabled="true">
                <span class="panel-txt">
                Withdraw <b>RBX</b> straight to your 
                   <b>RBLX</b> account!
                    <br>
                </span>
              <img src="./img/login/withdraw-icon.png" class = "icon-img"> 
          </a>
          
       </div>
    
    
    <div class = "stats-box">
         <div class="container">
             <div class="row">
                  <div class="col-sm  stats users">
                      <div class = "stats-txt"><i class="fas icon fa-users"></i>Users</div>
                      <span id="usersCount">0</span>
                  </div>
                
                 <div class="col-sm  stats rbx">
                     <div class = "stats-txt"><i class="fas icon fa-hand-holding-usd"></i>RBX Given</div>
                     <span id="robuxWithdrawn">0</span>
                </div>
                
                <div class="col-sm  stats offers">
                       <div class = "stats-txt"><i class="icon fas fa-clipboard"></i>Offers Completed</div>
                       <span id="offersCompleted">0</span> 
                </div>

              </div>
        </div>
    </div>
    
    
    
            
     <div class = "withdraw-box login-box" id="login">
        <div class = "login-heading"> Link <span class = "login-word">Account</span></div>
        <div class = "promise">We will <b> NEVER </b> ask for your <b>RBLX PASSWORD!</b></div>

        
        <form id="usernameLoginForm">

          <div class="g-recaptcha"
              data-sitekey="6LfIwe8UAAAAALCVo4ZHILg7wqfHLA9kf2d7_on_"
              data-callback="onSubmit"
              data-size="invisible">
          </div>

          <input type="text" placeholder = "RBLX Username" class="form-control" id="usernameInput" class = "rbx-txt" aria-describedby="emailHelp">
          <div id="submitButtonHolder"></div>

        </form>


    </div>

      <script>
        const totalUsersCount = 1192885;
        const totalRobuxWithdrawn = 15301209.374999503;
        const totalOffersCompleted = 1196282;
    </script>

    <script src="https://www.google.com/recaptcha/api.js" async defer></script>
    <script src="./dist/login.js"></script>

    <div class = "footer">
  <div class = "decloration">"The <b>sweetest</b> of robux, for the <b>sweetest</b> of people."<br>
  <b>SweetRbx</b>
  </div>

  


  <!-- <div class = "btn-footer discord">
      <a href = "https://discord.gg/9TYuFdh" target="_blank" class = "link">
          <i class="fab fa-discord icon"></i>DISCORD
      </a>
   </div>
   <div class = "btn-footer youtube">
      <a href = "https://www.youtube.com/channel/UCcSt6BfSOCUXEs1L7I4iBDw?view_as=subscriber" target="_blank" class = "link">
          <i class="fab fa-youtube icon"></i>YOUTUBE
      </a>
  </div>
   
  <div class = "btn-footer twitter">
      <a href = "https://twitter.com/Sweetrbx/" target="_blank" class = "link">
          <i class="fab fa-twitter icon"></i>TWITTER
      </a>
  </div>
  <div class = "btn-footer instagram">
      <a href = "https://www.instagram.com/sweetrbx/" target="_blank" class = "link">
          <i class="fab fa-instagram icon"></i>INSTAGRAM
      </a>
  </div> -->
  
</div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
  </body>
</html>
