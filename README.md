# Project_RestaurantBakso


# TAMPILAN LOGIN

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <style>
    
        body {
            background-color: #AEE2FF;
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
        }

        input {
            background-color: #f0f0f0;
            border: 1px solid #ccc; /* Added border style */
            border-radius: 10px;
            padding: 10px;
            margin-bottom: 20px;
            width: 80%;
            font-size: 14px;
            font-weight: 300;
            box-sizing: border-box;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }

        .form-container {
            background-color: #ffffff;
            border-radius: 10px;
            padding: 2.5rem;
            text-align: center;
            max-width: 400px;
            margin: 0 auto;
        }

        .form-control-user {
            border: 1px solid #ccc; /* Added border style */
            border-radius: 10px;
            padding: 0.75rem;
        }

        .small {
            color: #2C3E50;
        }

        .card {
            border-radius: 15px;
        }
        
        .card-body {
            padding: 2rem;
        }

        .btn-user {
            background-color: #00A9FF; /* Warna latar belakang */
            color: #ffffff; /* Warna teks */
        }

        .btn-user:hover {
            background-color: #427D9D; /* Warna latar belakang saat hover */
            color: #ffffff;
        }

    </style>
</head>

<body class="bg-gradient-primary">

    <div class="container">

        <!-- Outer Row -->
        <div class="row justify-content-center">

            <div class="col-lg-7">

                <div class="card o-hidden border-0 shadow-lg my-5">
                    <div class="card-body p-0">
                        <!-- Nested Row within Card Body -->
                        <div class="row">
                            <div class="col-lg">
                                <div class="form-container">
                                    <div class="text-center">
                                        <h1 class="h4 text-gray-900 mb-4">LOGIN</h1>
                                    </div>
                                    <form class="user">
                                        <div class="form-group">
                                            <input type="text" class="form-control form-control-user" id="email" name="email" placeholder="Email Address">
                                        </div>
                                        <div class="form-group">
                                            <input type="password" class="form-control form-control-user" id="password" name="password" placeholder="Password">
                                        </div>
                                        <button type="submit" class="btn btn-user btn-block">
                                            Login
                                        </button>
                                    </form>
                                    <hr>
                                    <div class="text-center">
                                        <a class="small" href="forgot-password.html">Forgot Password?</a>
                                    </div>
                                    <div class="text-center">
                                        <a class="small" href="registration.php">Create an Account!</a>
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
```

![image](https://github.com/Aliyahasmarani/Project_RestaurantBakso/assets/115197672/cb1384fe-3861-486e-b83a-1a2b5979840c)

# TAMPILAN CREATE ACCOUNT

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>Register</title>

    <style>
        /* General Styles */
        body {
            background-color: #AEE2FF;
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            margin-top: 50px;
            max-width: 50%; /* Set max-width to 50% */
            margin-left: auto;
            margin-right: auto;
        }

        /* Card Styles */
        .card {
            background-color: #f7f7f7;
            border: none;
            border-radius: 15px;
            overflow: hidden;
        }

        .card-body {
            padding: 30px;
        }

        /* Input Styles */
        input {
            background-color: #f0f0f0;
            border: 1px solid #ccc; /* Added border style */
            border-radius: 10px;
            padding: 10px;
            margin-bottom: 20px;
            width: 80%;
            font-size: 14px;
            font-weight: 300;
            box-sizing: border-box;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }

        input:focus {
            outline: none;
            border-color: #008cff; /* Change border color on focus */
        }

        /* Button Styles */
        button {
            background-color: #008cff;
            border: none;
            border-radius: 25px;
            color: white;
            padding: 12px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 14px;
            margin: 4px 2px;
            cursor: pointer;
            box-sizing: border-box;
        }

        button:hover {
            background-color: #0074d9;
        }

        /* Register Button Styles */
        .btn-daftar {
            background-color: #00A9FF;
        }

        .btn-daftar:hover {
            background-color: #427D9D;
        }

        /* Link Styles */
        .link {
            color: #888888;
            font-size: 12px;
            text-decoration: none;
            transition: color 0.3s;
        }

        .link:hover {
            color: #2C3E50;
        }

        /* Center Buttons and Links */
        .text-center {
            text-align: center;
        }
    </style>
</head>

<body>

    <div class="container">
        <div class="card">
            <div class="card-body">
                <!-- Nested Row within Card Body -->
                <div class="row">
                    <div class="col-lg-5 d-none d-lg-block bg-register-image"></div>
                    <div class="col-lg-7">
                        <div class="p-5">
                            <div class="text-center">
                                <h1 class="h4 text-gray-900 mb-4">Create an Account!</h1>
                            </div>
                            <form class="user">
                                <div class="form-group row">
                                    <div class="col-sm-6 mb-3 mb-sm-0">
                                        <input type="text" class="form-control form-control-user" id="fullname" name="fullname"
                                            placeholder="Full Name">
                                    </div>
                                </div>
                                <div class="form-group">
                                    <input type="email" class="form-control form-control-user" id="email" name="email"
                                        placeholder="Email Address">
                                </div>
                                <div class="form-group row">
                                    <div class="col-sm-6 mb-3 mb-sm-0">
                                        <input type="password" class="form-control form-control-user"
                                            id="password1" name="password1" placeholder="Password">
                                    </div>
                                    <div class="col-sm-6">
                                        <input type="password" class="form-control form-control-user"
                                            id="password2" name="password2" placeholder="Repeat Password">
                                    </div>
                                </div>
                                <div class="text-center"> <!-- Centered the buttons and links -->
                                    <button class="btn btn-primary btn-user btn-block btn-daftar">
                                        Register Account
                                    </button>
                                    <hr>
                                    <a class="link" href="forgot-password.html">Forgot Password?</a><br>
                                    <a class="link" href="login.php">Already have an account? Login!</a>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</body>

</html>
```

![image](https://github.com/Aliyahasmarani/Project_RestaurantBakso/assets/115197672/d842db80-982c-455b-a2e0-bc529cad7495)



