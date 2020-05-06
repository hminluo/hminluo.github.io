---
title: "About Me"
permalink: /about/
---

<html>
<head>
<style>

.page {
  padding-right:0px;
}

.p1 {
    font-size:15px;
    margin-top: 10px;
    margin-bottom: 40px;
    text-align:left;
    padding: 20px;
    padding-top: 50px;
    background:rgba(255,255,255,0.5);
    line-height: 1.8;
    font-family: Montserrat,sans-serif;
}
.post-container {
 display: flex;
 padding: 20px;
 justify-content: center;
}

.card {
    margin: 20px;
    border-radius: 10px;
    background-color: #ffffff;
    overflow: hidden;
    width:60%;
}
.profile1 {
  object-fit: cover;
  object-position: 100% 50%;
  width: 200px;
  height: 200px;
}
.profile2 {
  object-fit: cover;
  object-position: 30% 40%;
  width: 200px;
  height: 200px;
}
.pic{
	border-radius:50%;
      width: 200px;
      height: 200px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 50%;
      margin: auto;
      overflow: hidden;
      transition: all 0.2s ease-in-out;
}
.img-container {
      display: flex;
      align-items: center;
      width: 100%;
      height: 200px;
      padding: 20px 0px;
}
    .pic:hover{
        width: 160px;
        height: 160px;
    }
@media (max-width: 360px){
   .post-container {
    flex-wrap: wrap;
    padding: 0px;
}
   .card {
   width: 90%;
}
}
</style>
</head>
<body>

<div class="post-container">
<div class="card">
<div class="img-container">
<img src="https://raw.githubusercontent.com/hminluo/hminluo.github.io/master/assets/images/profile.png" alt="Avatar" class="pic profile1">
</div>
<p class='p1'>
<b>Branch Manager</b>
<br><br>
<b>Min</b> is a (allegedly)breaking-and-(attempt to)fixing things enthusiast. She has a piece of paper stating she has a master's degree from University of Central Florida in Statistical Computing with a focus on Data Mining. She uses Max as a model in her drawings.
</p>
</div>
<div class="card">
<div class="img-container">
        <img src="https://raw.githubusercontent.com/hminluo/hminluo.github.io/master/assets/images/Max.jpg" alt="Avatar" class="pic profile2">
</div>
<p class='p1'>
<b>Assistant Branch Manager</b>
<br>
<br>
<b>Max</b> is a corgi/foxhound-looking mutt. He holds a PhD(og) degrees in Food Science, and Front-End Security from an unaccredited online university. He claims he's at least 6 ft when he's standing on a high chair. He does modeling as a side gig.
</p>

</div>
</div>

</body>
</html>
