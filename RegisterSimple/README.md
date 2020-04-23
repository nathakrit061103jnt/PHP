# Register Login PHP/MBBootstrap and MYSQL
## ตัวอย่างการสร้างระบบ Register เเละ Login เเบบง่ายๆ โดยใช้ PHP MBBootstrap4 เเละ Mysqli
## เว็บไซต์ออกเเบบหน้าจอการล็อกอิน https://mdbootstrap.com/
### ดังนี้
 1. สร้างไฟล์ index.php เพื่อสร้างหน้า Login
       <!DOCTYPE html>
           <html lang="en">
              <head>
               <meta charset="UTF-8">
               <meta name="viewport" content="width=device-width,initial-scale=1.0">
            <title>Register & Login</title>
        </head>
        <body>
            
        </body>
        </html>

2. ทำการ link [MBBootstrap](https://mdbootstrap.com/md-bootstrap-cdn/) เข้ามา

<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Register & Login</title>
    <!-- Font Awesome -->
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
        <!-- Google Fonts -->
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap">
        <!-- Bootstrap core CSS -->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet">
        <!-- Material Design Bootstrap -->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.16.0/css/mdb.min.css" rel="stylesheet">
    </head>
    <body>

        
        <!-- JQuery -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
        <!-- Bootstrap tooltips -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.4/umd/popper.min.js"></script>
        <!-- Bootstrap core JavaScript -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/js/bootstrap.min.js"></script>
        <!-- MDB core JavaScript -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.16.0/js/mdb.min.js"></script>
    </body>
    </html>

3. ส้รางหน้าจอการ Login ที่ index.login
    <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Register & Login</title>
        <!-- Font Awesome -->
            <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
            <!-- Google Fonts -->
            <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap">
            <!-- Bootstrap core CSS -->
            <link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet">
            <!-- Material Design Bootstrap -->
            <link href="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.16.0/css/mdb.min.css" rel="stylesheet">
        </head>
        <body>

            <div class="container ">
                    <form  class="border border-light p-5 my-5">

                            <p class="h4 mb-4 text-center">Sign in</p>

                            <input type="text" id="" class="form-control mb-4" placeholder="username">

                            <input type="password" id="" class="form-control mb-4" placeholder="password">

                            <div class="d-flex justify-content-between">
                                <div>
                                    <a href="">Forgot password?</a>
                                </div>
                            </div>

                            <button class="btn btn-info btn-block my-4" type="submit">Sign in</button>

                            <div class="text-center">
                                <p>Not a member?
                                    <a href="">Register</a>
                                </p>

                                <p>or sign in with:</p>
                                <a type="button" class="light-blue-text mx-2">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a type="button" class="light-blue-text mx-2">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a type="button" class="light-blue-text mx-2">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a type="button" class="light-blue-text mx-2">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div>
                    </form>
            </div>
            
            <!-- JQuery -->
            <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
            <!-- Bootstrap tooltips -->
            <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.4/umd/popper.min.js"></script>
            <!-- Bootstrap core JavaScript -->
            <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/js/bootstrap.min.js"></script>
            <!-- MDB core JavaScript -->
            <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.16.0/js/mdb.min.js"></script>
        </body>
        </html>

![Image Alt](/images/login.png)