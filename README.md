<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>project 1</title>
</head>
<link rel="stylesheet" href="css/style.css">
<style>
    /* css reset */
    body
    {
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('img/gym3.jpg');
       

    }
    .left
    {
        /* border: 3px solid rgb(238, 110, 110); */
        display: inline=block;
        top: 2px;
        position: absolute;
        left: 50px;


    }
    .right
    {
        position: absolute;
        right: 50px;
        top: 20px;
        /* border: 3px solid rgb(137, 204, 167); */
        display: inline=block;

    }

    .mid
    {
        /* border: 3px solid rgb(194, 216, 114); */
        display: block;
        width: 35%;
        margin: 20px auto;

    }
    .navbar li
    {
        display: inline-block;
        font-size: 17px;
    }
    .navbar li a
    {
        color: white;
        text-decoration: none;
        padding: 20px 20px;
    }
    .navbar li a:hover
    {
        text-decoration: underline;
        color:turquoise;
    }
    .navbar li a.active
    {
        color: yellowgreen;
    }
    .left img
    {
        width: 58px;
        filter: invert(100%);
    }
    .left div
    {
        text-align: center;
        font-size: 19px;
        color: orange;
        line-height: 0px;
    }
    .btn
    {
        margin: 0px 10px;
        background-color:black;
        color: white;
        padding: 3px 8px;
        border: 3px solid goldenrod;
        border-radius: 5px;
        font-size: 15px;
        cursor: pointer;
    }
    .btn:hover
    {
        background-color: grey;
    }
    .harry
    {
    border: 4px solid white;
    margin: 106px 81px;
    padding: 28px;
    width: 33%;
    border-radius: 20px;
    }
    .formgroup input
    {
        text-align: center;
        border: 3px solid lightslategrey;
        margin: 15px 167px;
        border-radius: 10px;
        
    }
     h2
    {
        text-align: center;
    }
    .btn1
    {
        margin: 0px 206px;
        background-color:black;
        color: white;
        padding: 3px 8px;
        border: 3px solid goldenrod;
        border-radius: 5px;
        font-size: 15px;
        cursor: pointer;
    }

    
</style>
<body>
    <header class ="container">
        <div class="left">
            <img src="img/gym5.jpeg" alt="logo">
            <div>santhosh fitness</div>
        </div>
        <div class="mid">
           <ul class="navbar">
               <li ><a href=" " class="active">Home</a></li>
               <li ><a href="#">About us</a></li>
               <li ><a href="#">Fitness calculator</a></li>
               <li ><a href="#">contact us</a></li>
           </ul>
        </div>
        <div class="right">
            <button class="btn">call us now </button>
            <button class="btn">Email us  </button>
           
        </div>

    </header>
    <div class="harry">
        <h2>Join The Best Gym In Universe</h2>
        <form action="noaction.php">
            <div class="formgroup">
                <input type="text" name=""placeholder="enter your name">
            </div>
            <div class="formgroup">
                <input type="text" name=""placeholder="enter your girlfriend name">
            </div>
            <div class="formgroup">
                <input type="text" name=""placeholder="enter your ages">
            </div>
            <button class="btn1">Submit</button>
            
        </form>
    </div>
</body>
</html>
