# portfolio
# first page of portfolio


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <div style="float:left; width:10%; position: fixed;">

        <a href="portfolio.html"> <button id="home" class="disable_button"> <img src="home-pic-2.png" height="100px"
                    width="100px" /></button> </a> <br>



        <a href="about.html"> <button id="about" class="button"><img src="about.png" height="100px"
                    width="100px" /></button> </a> <br>

        <a href="education.html"> <button id="education" class="button"><img src="education.png" height="100px"
                    width="100px" /></button> </a> <br>

        <a href="skills.html"> <button id="skills" class="button"> <img src="skills.png" height="100px"
                    width="100px" /></button> </a> <br>

        <a href="contact.html"> <button id="contact" class="button"><img src="contacts.png" height="100px"
                    width="100px" /></button> </a> <br>


    </div>


    <div style="float:right; height: 30px; width:85%; padding-left:10%;">
        <p>
            MD AYAZUDDIN </p>
            <p1> Quality Specialist at Amazan</p1>
            <br>
        
    </div>




    <style>
        body {
            color: aliceblue;
            background-color: black;
            background-image: url("me_black.jpeg");
            background-repeat: no-repeat;
            background-position: right bottom, left top;
            background-attachment: fixed;
            background-size: contain;
        }

        p {
            font-size: 80px;
        }
        p:hover{
            font-size: 100px;
            
        }

        p1 {
            font-size: 40px;
            padding-left: 50px;
        }

        .button {
            position: relative;
            left: -40px;
            transition: 0.3s;


        }

        .button:hover {
            opacity: 0.6;
            left:0px;

        }

        .disable_button {
            opacity: 0.3;
            cursor: not-allowed;
        }

        button:active {
            background-color: #5f6463;
            box-shadow: 0 5px #666;
            transform: translateY(4px);
        }

        .disable_button {
            opacity: 0.3;
            cursor: not-allowed;
        }
        
        .disable_button:hover {
            opacity: 0.6;
            left:0px;
        }

        .disable_button:active {
            background-color: #5f6463;
            box-shadow: 0 5px #666;
            transform: translateY(4px);
        }
    </style>
</body>

</html>
