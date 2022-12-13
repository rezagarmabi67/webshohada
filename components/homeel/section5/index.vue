<template>
    <div class="home-sec-5 w100 relative dis-center">
        <img class="absolute back-sec-5" src="~/public/img/6.svg" alt="" />
        <label class="absolute">برنامه <span>آموزشی</span></label>
        <section class=" over-h">
            <table class="w100">
                <tr>
                    <th>شنبه</th>
                    <th>یک شنبه</th>
                    <th>دو شنبه</th>
                    <th>سه شنبه</th>
                    <th>چهار شنبه</th>
                    <th>پنج شنبه</th>
                </tr>
                <tr>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    
                </tr>
                
                <tr>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    <td>
                        <strong>کاراته</strong>
                        <span>10:00-11:00</span>
                        <p>پاشایی</p>
                    </td>
                    
                </tr>
            </table>
        </section>
    </div>
</template>
<style>
.home-sec-5{
    height: 930px;
}
.home-sec-5 .back-sec-5 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  top: 0;
}

.home-sec-5 label{
    top: 40px;
    color: #eee;
    font-size: 30px;
}

.home-sec-5 label span{
    color: var(--bg1);
}
.home-sec-5 section{
    width: 81%;
    height: 680px;
    z-index: 10;
    border-top: 1px solid var(--bg1);
    margin-top: 30px;
    background: rgba(68, 68, 68, 0.726);
}
.home-sec-5 section table:nth-child(1){
    height: 50px;
}

.home-sec-5 section table tr{
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;

}
.home-sec-5 section table tr th, .home-sec-5 section table tr td{
    width: 180px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-bottom: 1px solid rgba(119, 119, 119, 0.215);
}
.home-sec-5 section table tr th{
    color: #aaa;
    height: 40px;
    background: #222;
}
.home-sec-5 section table tr td{
    height: 150px;
    color: #ddd;
}
.home-sec-5 section table tr td{
    display: flex;
    flex-direction: column;
    gap: 15px;
}
.home-sec-5 section table tr td strong{
    font:  bolder 18px 'IRANSans';

}
.home-sec-5 section table tr td span{
    color: var(--bg1);
}
.home-sec-5 section table tr td p{
    color: #aaa;
    font-size: 12px;
}
</style>