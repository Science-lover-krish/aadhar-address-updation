<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to aadhar website for data updation</title>
    <style>  #forgot{position: absolute;top: 570px;left: 184px;color: seagreen;}

        #details {
            position: absolute;
            top: 334px;
            left: 134px;
            border-radius: 6px;
            box-sizing: content-box;
            margin: 2px 2px 2px 2px;
            padding: 20px 90px 20px 20px;
        }

        #password {
            position: absolute;
            top: 410px;
            left: 134px;
            margin: 2px 2px 2px 2px;
            padding: 20px 90px 20px 20px;
            border-radius: 6px;
        }

        #submit {
            position: absolute;
            top: 489px;
            left: 134px;
            margin: 1px 2px 1px 2px;
            padding: 20px 115px 20px 115px;
            border-radius: 6px;
            background-color: #1877f2;
            color: white;
            font-family: inherit;
            font-size: 20px;
        }
        /* #cb {
                position: absolute;
                top: 500px;
                left: 200px;
                border: 2px solid black;
                border-radius: 2px;
                height: 140px;
                width: 100px;
                margin: 2px;
                padding: 20px;
                background-color: turquoise;
                border-radius: 10px;
                font-style: italic;
                box-shadow: 10px -10px black;
            }

            #ln {
                position: absolute;
                top: 500px;
                left:20px;
                border: 2px solid black;
                border-radius: 2px;
                height: 140px;
                width: 100px;
                margin: 2px;
                padding: 20px;
                background-color: turquoise;
                border-radius: 10px;
                font-style: italic;
                box-shadow: 10px -10px black;
            }

            #hn {
                position: absolute;
                top: 720px;
                left: 100px;
                border: 2px solid black;
                border-radius: 2px;
                height: 140px;
                width: 100px;
                margin: 2px;
                padding: 20px;
                background-color: turquoise;
                border-radius: 10px;
                font-style: italic;
                box-shadow: 10px -10px black;
            } */

        .box {
            background-color:cadetblue;
             /* rgb(43, 42, 85); */
            border: black;
            position: absolute;
            top: 44px;
            left: 900px;
            height: 500px;
            width: 400px;
            margin: 2px;
            padding: 90px 90px 90px 90px;
        }
        #login{color: teal;position: absolute;top: -8vh;right: 10vw;font-size: 520%;}
        body {
            background-color: black;
            color: white;word-wrap: break-word;
        }

        #header {
            background-color:teal;
            border: 2px solid black;
            display: inline-block;
            size: 100vh;position: relative;top: 20vh;left: 0vw;border-radius: 20px;padding:20 20 20 20;
margin: 10px;        }
#heading{font-family: 'Courier New', Courier, monospace;width: 50vw;font-weight: lighter;font-size: medium;}
        #aadharlogo{height: 20vh;position: absolute;top: 0vh;left: auto;right:50vw}
        #aadharlogologin{position: absolute;top: 17vh;right: 12vw;height: 20vh;}
       #login:hover{  background-color: rgb(160, 224, 224);
        border: 3px solid darkorchid;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        text-decoration: dimgray;}
        #submit:hover{ background-color: rgb(17, 16, 16);
        border: 3px solid darkorchid;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        text-decoration: dimgray;}
    </style>
</head>

<body>
    <div id="header">
        <h1 id="heading">Welcome<br>Migrating to a new place for dwelling seems adventurous
            And YES! It is adventurous in the sense that we have to behold the damn situation
            which is the most required thing to prove our IDENTITY!!!
            THE AADHAR…
            The updated aadhar address when we have no other updated Proof of address!!
        Here's the solution for your problem!</h1>
        
        
        <h3>STEP-0</h3>
        <p>Login</p>
        <h3>STEP-1</h3>
        <p>Upload your proof of identity(Govt ID Card Any)</p>
        <!-- <a target="_blank" href="accepteddocs"></a> -->
         <h3>STEP-2</h3>
            <p>Verify your location by GPS</p>
            <h3>STEP-3</h3>
            <p>Edit data if required</p>
            <title>location should be near to gps captured location</title>
            
    </div>
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/cf/Aadhaar_Logo.svg/1200px-Aadhaar_Logo.svg.png" alt="aadhar" id="aadharlogo">
    <div class="box">
        <form action="backend.php">
            <h2 id="login">LOGIN</h2>
            <input type="text" class="form" id="details" placeholder="aadhar or phone number">
            <div>
                <input type="password" class="form" id="password" placeholder="otp">
            </div>
            <button id="submit" class="form" title="login">login
                <a href="/loged.html"> </a>
            </button>
            <!-- <a href="forgot.html" id="forgot" class="form">Forgot Your Details?</a> -->
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/cf/Aadhaar_Logo.svg/1200px-Aadhaar_Logo.svg.png" alt="aadhar" id="aadharlogologin">
            
        </form>

    </div>


</body>

</html>

    ![Welcome to aadhar website for data updation - Opera 31-10-2021 18_47_42](https://user-images.githubusercontent.com/93467650/139585463-a8d88c42-e3d8-44d0-a7c1-6677e515903e.png)
