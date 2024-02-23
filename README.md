<!doctype html>
<html lang="en">
<head>
  <title>Webleb</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link rel="stylesheet" href="https://unicons.iconscout.com/release/v2.1.9/css/unicons.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css">
<link rel="stylesheet" href="/css/styles.css">
</head>
<body>
<div id="stars"></div>
<div id="stars2"></div>
<div id="stars3"></div>
<div class="section">
  <div class="container">
    <div class="row full-height justify-content-center">
      <div class="col-12 text-center align-self-center py-5">
        <div class="section pb-5 pt-5 pt-sm-2 text-center">
          <h6 class="mb-0 pb-3"><span>Log In </span><span>Sign Up</span></h6>
                <input class="checkbox" type="checkbox" id="reg-log" name="reg-log"/>
                <label for="reg-log"></label>
          <div class="card-3d-wrap mx-auto">
            <div class="card-3d-wrapper">
              <div class="card-front">
                <div class="center-wrap">
                  <div class="section text-center">
                    <h4 class="mb-4 pb-3">Log In</h4>
                    <div class="form-group">
                      <input type="email" class="form-style" placeholder="Email">
                      <i class="input-icon uil uil-at"></i>
                    </div>	
                    <div class="form-group mt-2">
                      <input type="password" class="form-style" placeholder="Password">
                      <i class="input-icon uil uil-lock-alt"></i>
                    </div>
                    <a href="https://www.web-leb.com/code" class="btn mt-4">Login</a>
                    <p class="mb-0 mt-4 text-center"><a href="https://www.web-leb.com/code" class="link">Forgot your password?</a></p>
                      </div>
                    </div>
                  </div>
              <div class="card-back">
                <div class="center-wrap">
                  <div class="section text-center">
                    <h4 class="mb-3 pb-3">Sign Up</h4>
                    <div class="form-group">
                      <input type="text" class="form-style" placeholder="Full Name">
                      <i class="input-icon uil uil-user"></i>
                    </div>	
                    <div class="form-group mt-2">
                      <input type="tel" class="form-style" placeholder="Phone Number">
                      <i class="input-icon uil uil-phone"></i>
                    </div>	
                    <div class="form-group mt-2">
                      <input type="email" class="form-style" placeholder="Email">
                      <i class="input-icon uil uil-at"></i>
                    </div>
                    <div class="form-group mt-2">
                      <input type="password" class="form-style" placeholder="Password">
                      <i class="input-icon uil uil-lock-alt"></i>
                    </div>
                    <a href="https://www.web-leb.com/code" class="btn mt-4">Register</a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
</div>
</body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <title>Html coding</title>
  </head>
  <body>
    <div class="lantern"></div>
    <div class="lantern"></div>
    <div class="lantern"></div>
    <div class="lantern"></div>
  </body>
body {
  padding: 0;
  margin: 0;
  height: 100vh;
  display: flex;
  justify-content: space-evenly;
  align-items: flex-end;
  background-color: black;
}

lantern {
  height: 150px;
  width: 100px;
  background: rgb(255, 7, 7);
  position: relative;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  animation: up 50s infinite;
  box-shadow: 1px 1px 50px 10px red;
  border-radius: 20px;
}

.lantern::after {
  content: "";
  opacity: 80%;
  width: 30px;
  height: 30px;
  border-radius: 100%;
  position: absolute;
  background: rgb(255, 132, 0);
  animation: light 5s infinite;
}

@keyframes light {
  0%, 100% {
    box-shadow: 1px 1px 20px 10px rgb(255, 132, 0);
  }
  50% {
    box-shadow: 1px 1px 20px 15px rgb(255, 132, 0);
  }
}

@keyframes up {
  0%, 100% {
    transform: translateY(0vh);
  }
  50% {
    transform: translateY(-120vh);
  }
  90% {
    transform: translateY(0px);
  }
}

.lantern:nth-child(2){
  animation: up 40s infinite;
  background-color: rgb(60, 255, 0);
  box-shadow: 1px 1px 50px 10px rgb(60, 255, 0);
}
.lantern:nth-child(3){
  animation: up 55s infinite;
  background-color: rgb(0, 8, 255);
  box-shadow: 1px 1px 50px 10px rgb(0, 8, 255);
}
 .lantern:nth-child(4){
  animation: up 45s infinite;
  background-color: rgb(183, 0, 255);
  box-shadow: 1px 1px 50px 10px rgb(183, 0, 255);
}   
 .lantern:nth-child(5){
  animation: up 40s infinite;
  background-color: rgb(30, 63, 136);
  box-shadow: 1px 1px 50px 10px rgb(30, 63, 136);
}   
   
@media (max-width: 650px){
  .lantern:nth-child(5){
    display: none:
  }
}

 @media (max-width: 500px){
  .lantern:nth-child(4){
    display: none:
  }
}   
  
  @media (max-width: 300px){
  .lantern:nth-child(3){
    display: none:
  }
}

@media (max-width: 200px){
  .lantern:nth-child(2){
    display: none:
  }
}
(Leave empty if not needed) */                                      
