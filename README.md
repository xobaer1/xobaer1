<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>

    /* Source COde Link In Description */
    .container{
        display: grid;
        place-items: center;
    }
    .group-menu{
        cursor: pointer;
    }
   .dot{
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: black;
    margin-top: 4px;
   }
  .frame1{
    visibility: hidden;
  }
  .frame1 .info{
    font-size: 20px;
    color: white;
    border-bottom: 1px solid white;
    padding-top: 13px;
    cursor: pointer;
  }
  .frame1 .info:hover{
    background-color: #363333;
  }
  .frame1 .info span{
    margin-left: 10px;
  }
   .style{
    width: 200px;
    height: 300px;
    background-color: #111;
    margin-top: 5px;
    margin-left: -180px;
    border-radius: 10px;
   }

   .style2{
    width: 150px;
    height: 150px;
    background-color: #111;
    margin-left: 165px;
    margin-top: -75px;
    z-index: 999;
    border-radius: 10px;
   }
   .frame2{
    visibility: hidden;
   }
   .frame2 .setting-item{
    color: white;
    font-size: 20px;
    padding: 6px;
    border-bottom: 1px solid white;
    cursor: pointer;
   }

   .frame2 .setting-item:hover{
    background-color: #363333;
   }

</style>
<body background="redp.jpg">
    <div class="container">
    <div class="group-menu" onclick="fun()">
      <div class="dot"></div>
      <div class="dot"></div>
      <div class="dot"></div>
    </div>
    <!-- end group-menu -->

    <div class="frame1" id="frame1">
     <div class="info"><span>new</span></div>
     <div class="info"><span>history</span></div>
     <div class="info"><span>download</span></div>
     <div class="info"><span>view</span></div>
     <div class="info"><span>print</span></div>
     <div class="info"><span>bookmark</span></div>
     <div class="info" onclick="Setting()"><span>setting</span></div>
     <div class="info" onclick="remove()"><span>exit</span></div>
    </div>
        <!-- frame1 class end -->


    <div class="frame2" id="frame2">
        <div class="setting-item">DarkMode</div>
        <div class="setting-item">clear browser</div>
        <div class="setting-item">Logout</div>
        <div class="setting-item">Create Shortcut</div>
    </div>
    
 </div>
  <!--end container class  -->

  <script>
    function fun(){
        document.getElementById("frame1").style.visibility="visible";
        document.getElementById("frame1").classList.add("style");

     }

     function remove(){
        document.getElementById("frame1").classList.remove("style");
        document.getElementById("frame1").style.visibility="hidden";
        document.getElementById("frame2").classList.remove("style2");
     }

     function Setting(){
        document.getElementById("frame2").style.visibility="visible";
        document.getElementById("frame2").classList.add("style2");
     }
  </script> 
<hr>
 <p>
 <marquee scrollamount="9">
<font color="yellow" size="90">This is a website </font>

</marquee>
</p>
<hr>
<p align="center">
<br>
<button onclick="window.location.reload();">Reload</button>
 <br>
</p>
<br>
<br>
<br>
 <video controls width="320" hight="240" >
<source src="1.Introduction - IELTS Course by Munzereen Shahid.mp4" type="video/mp4">
 </video>
 <video controls width="320" height="240" >
  <source src="Jito.mp4" type="video/mp4">
 </video>
 <br>
 <img src="J&R.jpg" width="295" height="290">
 <br>
 <img src="carp.jpg width="320 height="240">
 <br>
 <form>
 comments: <textarea rows="3.5"cols="42">
 </textarea>
  <br>
  <br>
  <input type="submit" value="SUBMIT">
 </form>
 <hr>
 <br>
<hr>
<header>
<p align="center">
<font face="verdana">
<font color="ff00ff"size="10000000">Xobaer
</font>
<hr>
</header>
<br><br>
<table border="1" align="center">
<tr><th>
<font color="green"size="5">Form</font> 
</th></tr></table>
<br>
<form>
first name: <input type="text"><br>
Last name: <input type="text"><br><br>
User name: <input type="text"><br>
password: <input type="password"><br><br>
Mobile number: <input type="tel"><br><br>
Email: <input type="email"><br><br>
Date of birth: <input type="date"><br><br>
select images: <input type="file"><br><br>
Gender:
<input type="radio" name=" "> 💘
<input type="radio" name=" "> ❤️‍🔥
<input type="radio" name=" "> ⚠️
<br><br>
which player do you like :
<input type="checkbox">messi<br>
<input type="checkbox">Ronaldo 
<input type="checkbox">Neimar <br><br>
which team do you support:<select>
<option>Argentina</option>
<option>Brazil</option>
<option>Saudi arabia</option>
<option>purtogal</option>
<option>poland</option>
<option>Mexico</option>
<option>Canada</option>
<option>USA</option>
<option>No team</option>
</select>
</form>
</select><br><br>
comments: <textarea
rows="7"cols="42.5">Hi my name is Jubayar.  I am 18 years old. I study in 12. My college name is Dr mahbubur Rahman Mollah College(DMRC).</textarea><br><br>
<input type="submit" value="SUBMIT">
<br><br><br><br>
<table border="1">
<td>
(a<sub>1</sub>+b<sub>1</sub>)<sup>3</sup>
=a<sub>1</sub><sup>3</sup>+3a<sub>1</sub><sup>2</sup>
b<sub>1</sub>+3a<sub>1</sub>b<sub>1</sub><sup>2</sup>
+b<sub>1</sub><sup>3</sup>
</td>
</table>
<br><br>
<table border="1">
<td>
<header><u>Subject list</u></header>
<ol type="1">
<li>Bangla</li>
<li>Englush</li>
<li>ICT</li>
</ol></td>
</form>
<p>
<img src="Jubayar.jpg"border="30"title="⚠️Jobo"width="240"height="230">
</p>
<p>
<table border="1">
<tr>
<th>Name</th>
<th colspan="4">Telephone</th>
</tr>
<tr>
<td>taibullah</td>
<td>00009</td>
<td>999990</td>
<td>00008</td>
<td>888880</td>
</tr>
</table><br>
<audio controls class="audioplay"style="width:350px">
<source src="/storage/emulated/0/snaptube/download/SnapTube Audio/Mehdi Yakin _ Anas Otman - Arabic Soul(MP3_320K).mp3"type="audio/mp4">
 </audio>
<br>
<p><h1><font color="#ff00ff"><hr>
<marquee loop="">Dhaka Gulsan</marquee></font></h1>
<h2>
<marquee direction="right">Dhaka Uttara</marquee>
</h2>
<h2><marquee direction="up">Dhaka Demra</marquee></h2>
<h2><marquee scrolldelay="300">Banani </marquee></h2>
<h2><marquee scrollamount="70"direction="right">Dmrc</marquee></h2>
<font color="#00ffff">
<h1><marquee direction="down"scrollamount="10">Jobo</marquee></h1></font>
<h2><marquee scrollamount="400"direction="left">Marcidise</marquee>
<br><br><br><br><br><br>
<hr>
<dl>
<dt>jubayar</dt><br>
<dd>this is jubayar's discription</dd><br>
<dt>Taibullah</dt><br>
<dd>This is taibullah's discription</dd><br>
<dt>sabbir</dt><br>
<dd>this is sabbir's discription</dd><br>
<dt>Xiaomi</dt><br>
<dd>this is a Company</dd><br>
<dt>Apple</dt><br>
<dd>it’s one of the  biggest company of the whole world</dd><br>
</dl>
<hr><hr><hr>
<h2 align="center">ড. মাহবুবুর রহমান মোল্লা কলেজ</h2> <table border="1"align="right"><tr><td> দিবা</td></tr></table>
<br><h3 align="center">বর্ষ সমাপনী পরীক্ষা-২০২২</h3>

<table border="1">
<caption>শ্রেনিঃএকাদশ<br><table border="1"align="center"><tr><td>সময়সূচি</td></tr></table></caption>
<tr><th>পরীক্ষার <br>তারিখ ও বার</th><th>বিষয় </th>
<th> বিষয় কোড</th><th>সময়</th></tr>
<tr><td>১০/১০/২০২২<br>(সোমবার)</td>
<td>ইরেজি ১ম পত্র</td><td>১০৭</td><td>১ঃ৩০-৪ঃ৩০</td>
</tr>
<tr><td>১২/১০/২০২২<br>(বুধবার)</td><td>বাংলা ১ম পত্র</td><td>১০১</td><td>১ঃ৩০-৪ঃ৩০</td></tr>
<tr><td>১৬/১০/২০২২<br>(রবিবার)</td><td>রসায়ন ১ম পত্র/<br>ব্যবসায় সংগঠন ও ব্যবস্থাপনা ১ম পত্র/<br>সমাজকর্ম ১ম পত্র</td>
<td>১৭৬<br>২৭৭<br>২৭১</td><td>১ঃ৩০-৪ঃ৩০</td></tr>
<tr><td>১৮/১০/২০২২</td><td>তথ্য ও যোগাযোগ প্রযুক্তি</td><td>২৭৫</td><td>১ঃ৩০-৪ঃ৩০</td></tr>
<tr><td>২০/১০/২০২২<br>(মঙ্গলবার)</td><td>উচ্চতর গণিত ১ম পত্র/<br>ফিন্যান্স,ব্যাংকিং ও বিমা ১ম পত্র/<br>মনোবিজ্ঞান ১ম 
পত্র</td><td>২৬৫<br>২৯২<br>১২৩</td><td>১ঃ৩০-৪ঃ৩০</td></tr>
<tr><td>২৩/১০/২০২২<br>(বৃহষ্পতিবার)</td><td>পদার্থবিজ্ঞান ১ম পত্র/ <br>হিসাববিজ্ঞান ১ম পত্র/<br>অর্থনীতি ১ম পত্র</td>
<td>১৭৪<br>২৫৩<br>১০৯</td><td>১ঃ৩০-৪ঃ৩০</td></tr>
<tr><td>২৫/১০/২০২২<br>(মঙ্গলবার)</td><td>জীববিজ্ঞান ১ম পত্র/<br>উৎপাদন ব্যবস্থাপনা ও বিপণন ১ম পত্র/<br>
ইসলামের ইতিহাস ও সংস্কৃতি ১ম পত্র</td><td>১৭৮<br>২৮৬<br>২৬৭</td><td>১ঃ৩০-৪ঃ৩০</td></tr>
</table>
<a href="content://com.oneplus.filemanager/root/storage/emulated/0/Create%20form.html>" >Jub</a>

</body>
</html>
