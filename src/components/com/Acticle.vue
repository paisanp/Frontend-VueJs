<template>
    <div class="main">
        <h2>ข่าวสาร และบทความ ClickNext</h2>
        <div class="main-container">
            <div class="container">
                <img src="https://image.makewebeasy.net/makeweb/r_409x273/m14BHwk4P/Portfolio/thumbnail_smart_meet_msdbkk.png" alt="">
                <p><a href="">Smart Meeting Room : สำนักการแพทย์</a></p>
            </div>
            <div class="container">
                <img src="https://image.makewebeasy.net/makeweb/r_409x273/m14BHwk4P/Portfolio/Cover_MIS.png" alt="">
                <p><a href="">ระบบ MIS สําหรับการกํากับตรวจสอบสหกรณ์ทางการเงิน</a></p>
            </div>
            <div class="container">
                <img src="https://image.makewebeasy.net/makeweb/r_409x273/m14BHwk4P/Portfolio/Cover_OIC.png" alt="">
                <p><a href="">OIC ระบบฐานข้อมูลการประกันภัย-ชีวิต</a></p>
            </div>
        </div>
        <input type="submit" value="ดูเพิ่มเติม">
    </div>
</template>

<style scoped>
.main {
    text-align: center;
    padding: 0 5rem;
}

h2 {
    font-size: 40px;
    font-family: Poppins_SemiBold,Tahoma;
}
.main-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    padding: 0 5rem;
}

.container {
    margin-left: -2rem;
}


input {
    background-color: #e1032b;
    font-size: 15px;
    color: #fff;
    border: none;
    padding: 8px 16px;
    border-radius: 25px;
    margin-top: 2rem;
    margin-bottom: 3rem;
}

input:hover {
    background-color: #fff;
    color: #e1032b;
}


a {
    color: black;
    text-decoration: none;
    font-size: 18px;
    font-family: NotoSansThai_SemiBold,Tahoma;
}

a:hover {
    color: #e1032b;
}

img {
    width: 75%;
}
</style>