
<!doctype html>

<html>
    <head>
        <meta charset="utf-8">

        <title>IoI Team</title>
         <link rel="icon" type="image/x-icon" href="/pic/favicon.ico">
        <style>
        .haa{color: darkslategray;
            background-color:rgb(106, 125, 147);
            font-family: Helvetica, Verdana, sans-serif;
            font-size:200%;
            text-shadow: 2px 2px 4px #000000;
            padding: 30px;
            margin-bottom:5px;
        }
        .haaa{color: gray;
            font-family: Tahoma, Verdana, sans-serif;
            font-size:150%;
            text-shadow: 1px 1px 2px #000000;
            text-align: right;
            margin-right:100px;
        }
        .ha {color: dodgerblue; 
            font-size: 200%;
        }
        
        a:link {
            color: lightblue;
            background-color: transparent;
            text-decoration: none;
        }
        a:visited {
            color: white;
            background-color: transparent;
            text-decoration: none;
        }
        a:hover {
            color: lightblue;
            background-color: transparent;
            text-decoration: none;
        }
        
        
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: none;
            width: 100%;
            position: fixed;

        }

        li a{
            display: inline;
            color: gray;
            text-align: right bottom;
            font-size: 100%;
            padding: 10px 10px;
            text-decoration: none;
            float: right;
        }
        a:hover, .dropdown:hover .dropbtn {
            background-color: gray;
            border-radius: 4px;
        }
        a.active {
            background-color: none;
            color: gray;
            }

        li a:hover:not(.active) {
            background-color: none;
            color: none;
        }

        h1,h2,h3,h4,h5 {
            font-family: Helvetica, Verdana, sans-serif;
        }
.pg{
    text-align: right;
    margin-right: 80px;
    margin-top:-30px;
    margin-bottom:-20px;
    font-size:85%;
}
.pgb{
    text-align: right;
    margin-right: 80px;
    font-family: Helvetica, Verdana, sans-serif;
    font-size:120%;
}



.container {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
}
.box1{
  background-color: none;
  width: 400px;
  height:300px;
  border: 0px solid white;
  padding: 10px;
  margin-left: 20px;

}
.box2 {
  background-color: none;
  width: 500px;
  height:200px;
  border: 0px solid white;
  padding: 10px;
  margin: 0px;
  margin-left:auto;
  
}
.box4 {
  background-color: none;
  width: 600px;
  height:200px;
  border: 0px solid white;
  padding: 10px;
  margin-left: 200px;
  margin-right: 300px;
  margin-top:-30px;
}

.imgmb {
  border-radius: 10px;
  box-shadow: 0px 0px 10px;
}
img{
  border-radius: 2px;
  padding: 5px;
}
p{font-family:Helvetica;}
    body {
    background-image: url("/pic/3bg.jpg");
    background-repeat: repeat-y;
    background-position: none;
    background-size: 100%;
    background-attachment: fixed;
    margin-left: 0px;
    }
        </style>

        <!-- Load external CSS styles -->
        <link rel="stylesheet" href="styles.css">
        <script src="https://api.ohmnilabs.com/ohmni-api/Ohmni-standalone.js"></script>
    </head>

    <body style = "background-color:white;">
    
    <p id="C0"></p>
    <nav style="">
        <ul>
            <li><a href="#C0" title="HOME" style="font-family:Verdana;"><b>HOME</b></a></li>
            <li><a href="#C1" title="OVERVIEW"style="font-family:Verdana;"><b>PROJECT</b></a></li>
            <li><a href="#C2" title="MEMBERS"style="font-family:Verdana;"><b>MEMBERS</b></a></li>
            <li><a href="#C3" title="CONTROL"style="font-family:Verdana;"><b>CONTROL</b></a></li>
        </ul>
    </nav>
    <br>
    
    <header style="padding:1px 16px;height:100%;">
        <header><center><h1 id="C0" class="haa" style="font-size:350%;"><strong>ROBOTS SERVING IN SCHOOLS</strong></h1><br></center>         
         <pre class="haaa"><strong>This is a combination of IUH, OhmniLabs and IoI Team!</strong></pre>      
        
        <a href="/pic/RobotGIF.gif" style="margin-left:100px;"><img src="/pic/RobotGIF.gif" alt="gif" title="Nhấn để đến xem GIF" width="220" height="200"></a>        
        
        <a style="float:right; margin-right:150px;"href="/pic/IOITEAM.jpg"><img src="/pic/IOITEAM.jpg" alt="ioiteam" title="Nhấn để đến xem logo của IoI Team" width="130" height="70"></a>
        <a style="float:right;"href="https://ohmnilabs.com/"><img src="/pic/ohmni.jpeg" alt="ohmnilabs" title="Nhấn để đến trang chủ của Ohmnilabs" width="130" height="70"></a>
        <a style="float:right;"href="http://iuh.edu.vn/"><img src="/pic/Untitlediuh.png" alt="IUH"  title="Nhấn để đến trang chủ của IUH" width="130" height="70"></a>



            
            


            <p style="font-size:180%;color: black;text-indent: 30px; margin-left:70px;" id="C1"><strong><span style="font-size:300%;">O</span>VERVIEW</strong></p><hr width="85%" text-align="center">

        <p style="text-align: justify; margin-left: 70px; margin-right:230px;" >In recent years, strangers entering the school has resulted in unwelcome 
            consequences for pupils, students, the school such as stealing, test cheating
            and so on. We have seen those problems so we used the Ohmni robot to come up 
            ith a solution. We programmed the Ohmni robot to stand in classrooms, leacture 
            halls, exam rooms, and lap rooms to take attendance using the barcode on the 
            student’s card, then remind them to wash their hands and wearing a mask. 
            This is very important and indispensable during this pandemic. Simultaneously,
             the robot can go around the school campus (by controlling on the interface that
             it is available) to detect fire and then report the issue. In addition, students can 
             use the robot to look up information such as class times and ask for directions. 
             The school will improve the security level on campus with robot, as well as reduce l
             abor for teachers, increase teaching productivity, and improve the warning capacity to 
             bring the safety of the fire alarm operation and fire fighting. </p>

    <h1 style="font-size:180%; text-align: right; margin-right: 70px"><span style="font-size:300%;">P</span>ROJECT GOAL </h1>
    <hr width="85%" text-align="center">
        <p> 
            <p class="pgb"><strong>Goal 1</strong></p><br>
            <p class="pg">Automatic attendance according to the class at the lab.</p><br>
            <p class="pgb"><strong>Goal 2</strong></p><br>
            <p class="pg">Automatic fire alarm.</p><br>
            <p class="pgb"><strong>Goal 3</strong></p><br>
            <p class="pg">Provide class time for students.</p><br>
            <p class="pgb"><strong>Goal 4</strong></p><br>
            <p class="pg">Go around helping students find information.</p><br>
        </p> 
    
    <h1 style="text-align:left ;text-indent:30px;"><span style="font-size:300%;">T</span>ECHNICAL SOLUTION OVERVIEW </h1>
        <p style="text-align: justify ;  margin-left: 230px;"> Some high level overview of the proposed solution.   </p>
    <h2 style="margin-left:80px;"><span style="font-size:300%;">I</span>MPLEMENTATION PROCESS </h2>
    <div class="container">
        <div class="box1"><h3 style="margin-left:20px; "> I. Attendance: </h3>
        <p style="margin-left:10px; ">
            o The robot stands 30 minutes before the lab begins to wait for students. <br>
            o When students come, the robot will ask the information. Students take out their student card and the robot uses the built-in camera to scan the barcode: <br>           
            • Invalid barcode (more than three times): The robot does not allow the student to join the lab. If students still intentionally enter the lab, the robot will sound an alarm, notifying the security guard and the teacher. <br>
            • Valid barcode: the robot reports success and reminds students to always wear masks and use hand sanitizer.
            </p></div>

        <div class="box2"><h3 style="margin-left:15px; "> II. Fire alarm, incident report: </h3>
        <p style="margin-left:5px;"> 
        The robot employs the built-in camera to scan continuously while going around (by controlling on the interface that it is available). If a fire is detected, the robot will sound an alarm to warn others who are nearby. </p>
        <h3 style="margin-left:-5px;"> III. Class time information: </h3> 
         <p style="margin-left:-15px;"> 
            o When the robot is preparing to transmit a new lesson, it plays a notification sound 5 minutes ahead of time to give students time to prepare. </br> 
            o The robot continues to send notifications once the class begins </p>        
        </div> 
    </div>
    
    <div class="box4" style="float:center;">
    <h3 style="margin-left:10px;"> IV. Finding information: </h3> 
        <p> Outside of attendance time, the robot is programmed to go around the campus, helping students in their search for information. </p></div>
        
    <h2 style="text-align:left ;text-indent:30px "> HARDWARE </h2>
        <p class="kh" style="text-align: justify ;  margin-left: 30px; margin-right : 30px;"> Add hand anitizer to the tray for students. </p>
    <h2 style="text-align:left ;text-indent:30px "> SOFTWARE </h2> 
         <p class="kh" style="text-align: justify ;  margin-left: 30px; margin-right : 30px;"> 
            o Applied on WEB APP (Node.js, Python, HTML), interface on robot. </br>
            o Using a barcode on a student card scanned by a 4k camera on a screen and Python + OpenCV processing to identify students at the beginning of class. </br>
            o Go around is controlled remotely using a preset carrier interface. ( The robot can be controlled via the company's demo interface using the W, A, S, and D keys in accordance with ROS). </br>
            o Identify the fire by taking images from the 4k camera on the screen and processing them using Python programming. </br>
            o Set the time for the robot to signal the start of the lesson. </br>
            o Audio and video import and export libraries have API from supporting companies. (Node.js/Python) </br>
 </p>
    <h1 style="text-align:left;text-indent:30px"  > Project Plan & Milestones </h1>
        <b><p class="kh" style="text-align: justify ;margin-left: 30px; margin-right : 30px;" > 
            o From October 23 to October 30: Make a proposal to understand the robot overview and the functions of each part. </br>
            o From October 31 to November 14: Start programming the attendance and fire alarms.  </br> 
            o From November 15 to November 20: Program the timer for the robot.  </br> 
            o From November 20 to November 22: Run demo. </br></p></b></header >            
            
            
            <p id="C2" style="font-size:180%;color: black;" id="members"><strong> MEMBERS </strong></p>
        

            <hr><img class="imgmb" src="/pic/hoa.jpg" alt="hoa" width="300" height="300" style="float:right">
            <h3 class="ha">No.1</h3>
            <p style="font-size:180%">
            Full name: Trần Công Hòa<br>
            Date of birth: 02-04-2002<br>
            University: Industrial University of Ho Chi Minh City<br>
            Faculty: Electronics Technology<br>
            Phone: 0869209724<br>
            <a href="https://www.facebook.com/tranconghoax"><img src="/pic/unnamed.jpg" alt="tranconghoaFB" title="Nhấn để đến trang cá nhân của Hòa" width="30" height="30"></a>
            <a href="mailto:tranconghoa24@gmail.com"><img src="/pic/Gmail-1024x576.png" alt="tranconghoaMAIL" title="Nhấn để gửi mail cho Hòa" width="30" height="30"></a><br>
            </p>

            <hr><img class="imgmb" src="/pic/khanh.jpg" alt="khanh" width="300" height="300" style="float:left;">
            <h3 style="text-align:right;" class="ha">No.2</h3>
            <p style="text-align:right;font-size:180%">
            Full name: Doãn Đình Khánh<br>
            Date of birth: 03-10-2002<br>
            University: Industrial University of Ho Chi Minh City<br>
            Faculty: Electronics Technology<br>
            Phone: 0946654162<br>
            <a href="https://www.facebook.com/profile.php?id=100008677005968"><img src="/pic/unnamed.jpg" alt="doaninhkhanhFB" title="Nhấn để đến trang cá nhân của Khánh" width="30" height="30"></a>
            <a href="mailto:doan.dinh.khanh.3.10@gmail.com"><img src="/pic/Gmail-1024x576.png" alt="doaninhkhanhMAIL" title="Nhấn để gửi mail cho Khánh" width="30" height="30"></a><br>
            </p>
            
            <hr><img class="imgmb" src="/pic/phuong.jpg" alt="phuong" width="300" height="300" style="float:right">
            <h3 class="ha">No.3</h3>
            <p style="font-size:180%">
            Full name: Trần Thị Mai Phương<br>
            Date of birth: 21-10-2000<br>
            University: Industrial University of Ho Chi Minh City<br>
            Faculty: Foreign Languages<br>
            Phone: 0372139860<br>
            <a href="https://m.facebook.com/profile.php?id=100007942188787&refsrc=deprecated&_rdr"><img src="/pic/unnamed.jpg" alt="tranthimaiphuongFB" title="Nhấn để đến trang cá nhân của Phương" width="30" height="30"></a>
            <a href="mailto:maiphuongkt2110@gmail.com"><img src="/pic/Gmail-1024x576.png" alt="tranthimaiphuongMAIL" title="Nhấn để gửi mail cho Phương" width="30" height="30"></a><br>
            </p>

            <hr><img class="imgmb" src="/pic/ha.jpg" alt="ha" width="300" height="300" style="float:left">
            <h3 style="text-align:right;" class="ha">No.4</h3>
            <p style="text-align:right;font-size:180%">
            Full name: Nguyễn Thị Thu Hạ<br>
            Date of birth: 08-10-2002<br>
            University: Industrial University of Ho Chi Minh City<br>
            Faculty: Electronics Technology<br>
            Phone: 0582145048<br>
            <a href="https://www.facebook.com/bo.bum.10"><img src="/pic/unnamed.jpg" alt="nguyenthithuhaFB" title="Nhấn để đến trang cá nhân của Hạ" width="30" height="30"></a>
            <a href="mailto:ntthnttt@gmail.com"><img src="/pic/Gmail-1024x576.png" alt="nguyenthithuhaMAIL" title="Nhấn để gửi mail cho Hạ" width="30" height="30"></a><br>
            </p>
            
            <hr><img class="imgmb" src="/pic/duy.jpg" alt="duy" width="300" height="300" style="float:right">
            <h3 class="ha">No.5</h3>
            <p style="font-size:180%">
            Full name: Đỗ Tuấn Duy<br>
            Date of birth: 05-12-2002<br>
            University: Industrial University of Ho Chi Minh City<br>
            Faculty: Electronics Technology<br>
            Phone: 0886242420<br>
            <a href="https://www.facebook.com/DTJ512"><img src="/pic/unnamed.jpg" alt="dotuanduyFB" title="Nhấn để đến trang cá nhân của Duy" width="30" height="30"></a>
            <a href="mailto:dotuanduy0512@gmail.com"><img src="/pic/Gmail-1024x576.png" alt="dotuanduyMAIL" title="Nhấn để gửi mail cho Duy" width="30" height="30"></a><br>
            <hr></p>

        
        
            <p class="C3"style="font-size:180%;color: black;"><strong> CONTROL </strong></p>

        <!-- Control page -->    
        <button type="button" onclick=say()>Good morning!</button>
        <button type="button" onclick=present()>Start the presentation!</button>
        <script>

        function say() {
            Ohmni.setSpeechLanguage("en-US");
            Ohmni.say("Good morning!")
        }
        function present() {
            Ohmni.setSpeechLanguage("en-US");
            Ohmni.say("Hello everyone.  Welcome to our project “ Robot serving in schools”.     Our team consists of 5 members. ....   In recent years, strangers entering the school has resulted in unwelcome consequences for pupils, students, the school such as stealing, test cheating and so on. We have seen those problems so we used the Ohmni robot to come up with a solution. We programmed the Ohmni robot to stand in classrooms, leacture halls, exam rooms, and lap rooms to take attendance using the barcode on the student’s card, then remind them to wash their hands and wearing a mask. This is very important and indispensable during this pandemic. Simultaneously, the robot can go around the school campus (by controlling on the interface that it is available) to detect fire and then report the issue. In addition, students can use the robot to look up information such as class times and ask for directions. The school will improve the security level on campus with robot, as well as reduce labor for teachers, increase teaching productivity, and improve the warning capacity to bring the safety of the fire alarm operation and fire fighting.     So we set 4 goals for this project. Firstly, robot can automatically take attendance according to class in the lab. Secondly, it can fire alarm automatically. Thirtly, Provide class time for students know when they forget or don’t know. Finally, Robot can go around helping students find information. Example when a student wants to go to the building A, it can guide and direct for the student. ")
        }
        </script>
        </header>

        
        
        <!-- Load external JavaScript -->
        <script src="scripts.js"></script>
        

</html>
