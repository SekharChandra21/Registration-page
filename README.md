# Registration-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration</title>
</head> 
<body>
    <div class=" container">
        <div id="text" align="center">HOTEL MANAGEMENT SYSTEM</div>
        <h1> REGISTER HERE</h1>
        <form action="#">
            <div class="user-detiles">
                <div class="input-box">
                    <span class="detiles">First Name : </span>
                    <input type="firstname" placeholder="Enter your firstname" required>
                </div>
                <div class="input-box">
                    <span class="detiles">Last Name : </span>
                    <input type="lastname" placeholder="Enter your lastname" required>
                </div>
                <div class="input-box">
                    <span class="detiles">Usaername : </span>
                    <input type="username" placeholder="Enter your username" required>
                </div>
                <div class="input-box">
                    <span class="detiles">Email : </span>
                    <input type="email" placeholder="Enter your Email" required>
                </div>
                <div class="input-box">
                    <span class="detiles">Phone Number : </span>
                    <input type="phone number" placeholder="Enter your Phone Number" required>
                </div>
                <div class="input-box">
                    <span class="detiles">Password : </span>
                    <input type="password" name="Password" placeholder="Enter your password" required>
                </div>
                <div class="input-box">
                    <span class="detiles">Confirm Password : </span>
                    <input type="password" name="Password" placeholder="Confirm your password" required>
                </div>
                <div class="gender-detiles">
                    <input type="radio" name="gender" id="dot-1">
                    <input type="radio" name="gender" id="dot-2">
                    <input type="radio" name="gender" id="dot-3">
                    <span class="gender-title">Gender :</span>
                    <div class="category">
                        <label for="dot-1">
                            <span class="dot one"></span>
                            <span class="gender">Male</span>
                        </label>
                        <label for="dot-2">
                            <span class="dot two"></span>
                            <span class="gender">Female</span>
                        </label>
                        <label for="dot-3">
                            <span class="dot three"></span>
                            <span class="gender">Others</span>
                        </label>
                         
                 <div class="button">
                    <input type="submit" value="Register">
                 </div>

            </div>
        </form>

    </div>
</body>
<style>

    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    h1{
        text-align: center;
        padding-top: 5px;
        color: #cf288a;
    }
    #text{
         color: #d6e411;
         font-size: 30pt;
         font-family: Arial, Helvetica, sans-serif;
         text-shadow:-2px 2px 0 black,
                     -4px 4px 0 black,
                     -6px 6px 0 black,
                     -8px 8px 0 black,
                     -10px 10px 0 black,
                     -12px 12px 0 black,
                     -14px 14px 0 black;
    }

    body{
        display: flex;
        height: 100vh;
        align-items: center;
        justify-content: center;
        padding: 10px;
        background: url("https://www.betasourcesoftware.com/images/hotel.jpg");
        background-repeat: no-repeat;
        background-size: 1500px 700px;
    }
    .container{
        max-width: 700px;
        width: 100%;
        background:transparent;
        padding: 25px 30px;
        border-radius: 5px;
    }
    .container .title{
        font-size: 25px;
        font-weight: 500;
        position: relative;
    }
    .container .title ::before{
        content: ' ';
        position: absolute;
        left: 0;
        bottom: 0;
        height: 3px;
        width: 30px;
    }
    .container form .user-detiles{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        margin: 20px 0 12px 0;
        color: rgb(109, 243, 31);
    }
    form .user-detiles .input-box{
        margin: 15px;
        width: calc(100%2-20px);
    }
    .user-detiles .input-box .detiles{
        display: block;
        font-weight: 500;
        margin-bottom: 5px;
    }
    .user-detiles .input-box input{
        height: 30px;
        width:100% ;
        outline: none;
        border-radius: 3px;
        border: 1px solid #ccc;
        padding-left: 15px;
        font-size: 16px;
    }
    .user-detiles .input-box input:focus,
    .user-detiles .input-box input:valid{
        border-color: #5cca86;

    }
    form .gender-detiles .gender-title{
        font-size: 20px;
        font-weight: 500;
        text-align:left;
    }
    form .gender-detiles .category{
        display: flex;
        width: 80%;
        margin: 14px 0;
        justify-content: space-between;
    }
    .gender-detiles .category label{
        display: flex;
        align-items: center;
        text-align: justify;
    }
    .gender-detiles .category .dot{
        height: 18px;
        width: 18px;
        background: #d9d9d9;
        border-radius: 50%;
        margin-right: 10px;
        border: 5px solid transparent;
        transition: all 0,3s ease;
    }
    #dot-1:checked ~ .category label .one,
    #dot-2:checked ~ .category label .two,
    #dot-3:checked ~ .category label .three{
        border-color: #d9d9d9;
        background: #9b59b6;
    }
    form input[type="radio"]{
        display: none;
    }
    form .button{
        height: 45px;
        margin: 45px 0;
        margin: 0;
        position: absolute;
        top: 50%;
        left: 50%;
         
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
    form .button input{
        height: 35px;
        width: 150%;
        outline: none;
        color: #fff;
        border: none;
        font-size: 18px;
        font-weight: 500;
        border-radius: 5px;
        letter-spacing: 1px;
        align-items:baseline;
        background: linear-gradient(135deg,#5cca86,#337492);;
    }

</style>
</html>
