<template>
  <div class="home-sec-4 w100 relative">
    <img class="absolute back-sec-4" src="~/public/img/6.svg" alt="" />
    <section>
      <span class="click-right"> &#10006; </span>
      <span class="click-left"> &#10006; </span>
      <label class="absolute">مربی <span>ما</span></label>
      <div class="display gap30 container-coachs">
        <div class="display home-sec-coach gap10">
          <div>
            <img src="~/public/img/trainer-1.jpg" alt="" />
          </div>
          <div class="tex-al-r dis-col gap10 sec-caption">
            <p class="name-coach">مجید پاشایی</p>
            <span>کاراته</span>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Voluptatem officia, velit quod soluta veritatis cupiditate
              similique magni iusto placeat minus aliquam! Repudiandae
              consequuntur voluptas, facere commodi illo tempora. Sapiente,
              exercitationem!
            </p>
            <div class="social-coach">
              <i>instagram</i>
              <i>telegram</i>
              <i>whatsapp</i>
            </div>
          </div>
        </div>
        <div class="display home-sec-coach gap10">
          <div>
            <img src="~/public/img/trainer-1.jpg" alt="" />
          </div>
          <div class="tex-al-r dis-col gap10 sec-caption">
            <p class="name-coach">مجید پاشایی</p>
            <span>کاراته</span>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Voluptatem officia, velit quod soluta veritatis cupiditate
              similique magni iusto placeat minus aliquam! Repudiandae
              consequuntur voluptas, facere commodi illo tempora. Sapiente,
              exercitationem!
            </p>
            <div class="social-coach">
              <i>instagram</i>
              <i>telegram</i>
              <i>whatsapp</i>
            </div>
          </div>
        </div>
        
      </div>
    </section>
  </div>
</template>
<style>
.home-sec-4 {
  height: 500px;
  margin-top: 100px;
}

.home-sec-4 .back-sec-4 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  top: 0;
}
.home-sec-4 section {
  padding: 50px 100px;
  text-align: center;
}

.click-right, .click-left{
  width: 35px;
  height: 35px;
  position: absolute;
  bottom: 80px;
  color: #ddd;
  font-size: 25px;
  background: var(--bg1hover);
  cursor: pointer;
}
.click-right{
  right: 100px;
}
.click-left{
  right: 145px;
}
.click-right:hover, .click-left:hover{
  background: var(--bg1);
}
.home-sec-4 label {
  width: 200px;
  height: 100px;
  padding: 20px;
  top: -80px;
  left: 50%;
  transform: translateX(-50%);
  color: #eee;
  font: bold 40px "IRANSans";
}
.home-sec-4 label span {
  color: var(--bg1);
}


.home-sec-coach {
  width: 550px;
  height: 320px;
  background-color: #333;
  overflow: hidden;
  z-index: 10;
  cursor: pointer;
}
.home-sec-coach:hover {
  background-color: #ddd;
  transition: all 0.4s;
}

.home-sec-coach:hover p,
.home-sec-coach:hover div i {
  color: #111;
  transition: all 0.4s;
}
.home-sec-coach .social-coach {
  margin: 30px 0;
}
.social-coach i {
  padding: 0 5px;
  color: #eee;
}

.home-sec-coach div p {
  color: #eee;
}
.home-sec-coach div span {
  color: var(--bg1);
}
.sec-caption {
  height: 90%;
}
.sec-caption .name-coach {
  font-size: 18px;
  font-weight: bold;
}
</style>