# clothing-store
Clothing store

<html lang="en">
    <head>

        <meta charset="X-UA-Compatible" content="IE-edge">
        <meta http-equiv="X-UA-Compatible" content="IE-edge">
        <meta name="viewport" content="width-device-width, initial-scale-1.0">

        <link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;1,100;1,300;1,400;1,700&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="style.css"
        <title>Clothing Store</title>
    </head>
    <body>


        <nav>

            <div class="navTop"></div>
            <div class="navItem"></div>
             <img src ="pic.01.png" alt="">

             <div>
                <div clas="navItemm"></div>
                  <div class="Search">
                    <input type="text " placeholder="Search...." class="searchinput">
                    <img src="./img/pic.03.jpg" width="20" height="20" alt="" class="searchicon">

                  </div>
                <div clas="navItemm"></div>
                <span class="limitedOffer">limitedOffer</span>
             </div>


            <div class="navBottom"></div> 


        </nav>
    </body>





</html>



body{
    font-family:  'Lato', sans-serif;
    padding: 0;
    margin: 0;
}

nav{
    background-color: brown;
    color: white;
    padding: 20px 50px;
}

.navTop{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
    
.search{
    display: flex;
    align-items: center;
    background-color: grey;
    padding: 10px 20px;
    border-radius: 10px;
}

.searchinput{
    border: none;
    background-color: transparent;
}

.searchinput ::placeholder{
    color:lightgrey;
}

.limitedoffer{
    font-size: 20px;
    border-bottom: 2px solid green;
    cursor: pointer;
}






