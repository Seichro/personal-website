<template>
  <div class = "whole-website">
<div class = "welcome-message">
  <p>Hi I'm Anthony.</p>
</div>
    <div class = "socials">
      <a href="https://www.linkedin.com/in/anthony-abubakar-017a4b24a/"><img src="../assets/linkedin.png" alt="LinkedIn" style="width:42px;height:42px;"></a>
      <a href="https://github.com/Seichro"><img src="../assets/github.png" alt="GitHub" style="width:54px;height:54px;"></a>
      <a href="https://devpost.com/iseichro?ref_content=user-portfolio&ref_feature=portfolio&ref_medium=global-nav"><img src="../assets/devpost.jpg" alt="DevPost" style="width:54px;height:54px;"></a>

    </div>

 <div class = "cat-picture">
       <img alt="Cat" src="../assets/cat.jpg" >
     </div>
       <div class = "who-am-i">
         <p>I'm Anthony Abubakar. I'm a Computer Science Freshman at UTD planning to minor in Math.</p>

         <p>I'm currently involved in <a href=https://acmutd.co/>ACM</a>, <a href=https://www.utdnebula.com/>Nebula Labs</a>, <a href=https://sg.utdallas.edu/>Student Government</a>, ECS Student Council, and <a href=https://urec.utdallas.edu/competitive/club/>Powerlifting Club</a>.</p>

         <p>Want to contact me?</p>
       </div>
    <!--<div class="popup" id="popup-1">
      <div class="overlay"></div>
      <div class="content">
        <div class="close-btn" onclick="togglePopup()">&times;</div>
        <h1>Title</h1>
        <p>bs bs bs bs bs bs</p>
      </div>
    </div>
    <button onclick="togglePopup()">Show Popup</button> -->
  </div>
</template>

<script>

document.title = 'Anthony\'s Website';
</script>

<style>
body, html{
  margin: 0;
  width:100%;
}
html{
  background-color: royalblue;
}

.whole-website{
  font-family: Monospace;
  align-items: center;
}
.welcome-message{
  margin-top: 15px;
  color: black;
  text-align: center;
  font-size: 50px;
  font-weight: initial;
}
.cat-picture{
  margin-top: 15px;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

.socials {
  text-align: center;
  background-color: white;
  border: 2px solid black;
  margin-left:39%;
  margin-right:39%;

  margin-bottom: 20px;
}
img {
  object-fit: contain;
}

.who-am-i{
  margin-left:200px;
  margin-right:200px;
  margin-top: 20px;
  border:2px solid white;
  padding: 10px;
  background-color: black;
  color: white;
  font-size:15px;
  text-align: center;
}

.popup .overlay {
  position: fixed;
  top: 0px;
  left: 0px;
  width: 100vw;
  height: 100vh;
  background:rgba(0,0,0.7);
  z-index:1;
  display:none;
}

.popup .content{
  position:absolute;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%) scale(0);
  background:#fff;
  width:450px;
  height:220px;
  z-index:2;
  text-align:center;
  padding:20px;
  box-sizing:border-box;
}

.popup .close-btn{
  position:absolute;
  right:20px;
  top:20px;
  width:30px;
  height:30px;
  background:#222;
  color:#fff;
  font-size:25px;
  font-weight:600;
  line-height:30px;
  text-align:center;
  border-radius:50%;
}

.popup.active .overlay{
  display:block;
}
.popup.active .content {
  transition:all 300ms ease-in-out;
  transform:translate(-50%,-50%) scale(1);
}

</style>
