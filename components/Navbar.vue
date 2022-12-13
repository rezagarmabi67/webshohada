

<template>
  <div class="header w100 font-iran">
    <div class="padx50">
      <div class="display head-sec-1">
        <ul class="font12 display gap30">
          <li><p>02166620182</p></li>
          <li><p>شنبه الی پنج شنبه : 8 - 21</p></li>
        </ul>
        <div class="form-search">
          <form>
            <input type="text" />
            <span>جستجو</span>
          </form>
        </div>
      </div>
      <div class="head-sec-2 display">
        <ul class="display gap10">
          <li>
            <NuxtLink to="/">خانه</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/">درباره ما</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/">تماس با ما</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/">ثبت نام کلاس</NuxtLink>
          </li>
        </ul>
        <div>
          <p>باشگاه شهدا</p>
        </div>
      </div>
      <div class="head-sec-3">
        <ul class="font14">
          <li>
            <SportField/>
          </li>
         
        </ul>
      </div>

    </div>
    <slot />
  </div>
</template>
<style>
.header {
  height: 170px;
  background: #222;
  color: #eee;
}

.head-sec-1 {
  width: 80%;
  margin: 0 auto;
  padding: 10px;
  border-bottom: 1px solid #555;
}

.head-sec-1 li a {
  color: #eee;
}

.form-search form input {
  background: none;
  border-bottom: 1px solid var(--bg1);
}
.form-search form span {
  color: var(--bg1);
  font-size: 12px;
}

.head-sec-2{
  width: 90%;
  padding: 0 10px;
}
.head-sec-2 ul{
  margin-right: 120px;
  padding: 10px ;
  font-size: 14px;
}
.head-sec-2 ul li a{
  color: var(--bg1);
}
.head-sec-2 ul li{
  padding: 2px 5px;
}
.head-sec-2 ul li:hover{
  background: #eee;
  transition: all 0.4s;
}
.head-sec-3 {
  width: max-content;
  margin: 20px auto;
  padding: 10px;
}
.head-sec-3 ul {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.head-sec-3 ul li {
  padding: 3px 10px;
}
.head-sec-3 ul li:hover {
  background-color: var(--bg1);
  transition: all 0.4s;
}
.head-sec-3 ul li:not(.last) {
  padding: 3px 10px;
  border-left: 0.1em solid #555;
}
.head-sec-3 ul li a {
  color: #eee;
}
</style>