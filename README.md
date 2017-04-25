<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
body {font-family: "Times New Roman", Georgia, Serif;}
h1,h2,h3,h4,h5,h6 {
    font-family: "Playfair Display";
    letter-spacing: 5px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-padding w3-card-2" style="letter-spacing:4px;">
    <a href="#home" class="w3-bar-item w3-button">10ร้านห้ามพลาดในหาดใหญ่</a>
    <!-- Right-sided navbar links. Hide them on small screens -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">HOME</a>
      <a href="#menu" class="w3-bar-item w3-button">FOOD</a>
       </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1600px;min-width:500px" id="home">
  <img class="w3-image" src="thongwong1.jpg" alt="Hamburger Catering" width="1600" height="800">
  <div class="w3-display-middle w3-padding-large w3-black">
    <h1 class="w3-xxlarge">ขนมจีนบ้านทองวงค์</h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content" style="max-width:1100px">

  <!-- About Section -->
  <div class="w3-row w3-padding-64" id="about">
    <div class="w3-col m6 w3-padding-large w3-hide-small">
     <img src="thongwong2.jpg" class="w3-round w3-image w3-opacity-min" alt="หน้าร้าน" width="600" height="750">
    </div>

    <div class="w3-col m6 w3-padding-large">
      <h1 class="w3-center">ขนมจีนทองวงค์</h1><hr>
      <h5 class="w3-center">ขนมจีนขึ้นชื่อในหาดใหญ่</h5>
      <p class="w3-large">อิ่ม คุ้ม ครบ ไม่เกินร้อย ขนมจีนเส้นสด “ร้านขนมจีนบ้านทองวงศ์” หาดใหญ่ อิ่มคุ้ม กับร้าน “ขนมจีนบ้านทองวงศ์” เมืองหาดใหญ่ ขนมจีนเส้นสด ครบครันทั้งเครื่องเคียง ไก่ทอด ขนมหวาน และข้าวคลุกกะปิ ในราคาเบา ๆ แบงค์ร้อยเอาอยู่</p>
      <span class="w3-tag w3-red">ต้องลอง !</span>
      
    </div>
  </div>

  <hr>

  <!-- Menu Section -->
  <div class="w3-row w3-padding-64" id="menu">
    <div class="w3-col l6 w3-padding-large">
      <h1 class="w3-center">ข้อมูลร้าน</h1><br>
      <h4>เวลาเปิดร้าน</h4>
      <p class="w3-text-grey">จันทร์ - เสาร์: 08:30 - 15:00</p><br>

      <h4>ที่ตั้งและบรรยากาศ</h4>
      <p class="w3-text-grey">ร้านนี้ตั้งอยู่ตรงคลองเรียน 1 เยื้องกับร้านข้าวมันไก่เชฟหมง<br>
      ภายในร้านดูโล่ง โต๊ะที่นั่งถูกจัดวางเป็นระเบียบ ดูสะอาดสะอ้านน่านั่งมากครับ แถมมี Free WiFi</p><br>

      <h4>ช่วงราคา</h4>
      <p class="w3-text-grey">ต่ำกว่า 100 บาท</p><br>

      <h4>เบอร์ติดต่อ</h4>
      <p class="w3-text-grey">081-0925660</p><br>

      <h4>ช้อมูลอื่นๆ</h4>
      <p class="w3-text-grey">มีที่จอดรถ<br>
      เหมาะสำหรับมาเป็นกลุ่ม<br>
      มี 41-80ที่นั่ง </p>
    </div>

    <div class="w3-col l6 w3-padding-large">
      <img src="thongwong3.jpg" class="w3-round w3-image w3-opacity-min" alt="ขนมจีน" width="500" height="750">
    </div>
  </div>

  <hr>
<!-- End page content -->
<div class="w3-row-padding">
  <div class="w3-col s4"><img src="img_lights.jpg"></div>
  <div class="w3-col s4"><img src="img_nature.jpg"></div>
  <div class="w3-col s4"><img src="img_fjords.jpg"></div>
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-32">
  <p>contact us<a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

</body>
