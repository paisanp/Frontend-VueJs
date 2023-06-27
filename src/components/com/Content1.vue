<template>
    <div class="main">
        <img class="main-img"
            src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2Fsection_01_herobanner.jpg?v=202305101549"
            alt="">
        <div class="main-container">

            <div class="container">
                <p class="partner">STRATEGIC PARTNER</p>
                <img class="img-partner"
                    src="https://image.makewebeasy.net/makeweb/0/m14BHwk4P/Home/02_Partner.png?v=202305101549" alt="">
            </div>

            <div class="container ">
                <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/03___Stack_1_edite2.png?v=202012190947"
                    alt="">
                <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/03___Stack_2_edite2.png?v=202012190947"
                    alt="">
            </div>

            <div class="container service-container">
                <h1 class="service">SERVICE</h1>
                <p class="content-service">เราเป็นนักพัฒนาซอฟต์แวร์มืออาชีพที่เน้นกระบวนการพัฒนาซอฟต์แวร์แบบครบวงจร
                    เพื่อให้ลูกค้าได้รับผลงานที่มีคุณภาพและส่งมอบตรงเวลา</p>
            </div>
            
            <div class="back-img">
                <div class="container">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/05__Service_01_edit_1.png?v=202012190947"
                        alt="">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/05__Service_02_edit_1.png?v=202012190947"
                        alt="">
                </div>

                <div class="container">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/05__Service_03_edit_1.png?v=202012190947"
                        alt="">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/05__Service_04_edit_1.png?v=202012190947"
                        alt="">
                </div>

                <div class="container">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/05__Service_05_edit_1.png?v=202012190947"
                        alt="">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/05__Service_06_edit_1.png?v=202012190947"
                        alt="">
                </div>
            </div>

            <div class="container-content" style="margin-bottom: 40px;">
                <h1 style="font-size: 40px;">OUR WORK</h1>
                <div class="content-service">
                    <p>เราสร้างสรรค์ผลงานที่ใช่สำหรับคุณและนำไปใช้พัฒนาธุรกิจของคุณได้จริง </p>
                    <p>ด้วยทีมงานมืออาชีพมากประสบการณ์ที่เข้าใจธุรกิจคุณที่สุด</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>  
.main {}

.main-img {
    width: 100%;
}

.main-container {
    max-width: 1200px;
    margin: 0 auto;
}

.container {
    display: flex;
    justify-content: space-between;
}

@media screen and (max-width: 900px) {
    .container {
        display: block;
    }

    .container img {
        text-align: center;
        width: 40%;
    }
}

.container img {
    width: 100%
}

.container-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.service-container {
    padding: 1rem 1rem;
    justify-content: space-between;
}

.service {
    font-size: 40px;
    color: #212121;
    font-family: Poppins_SemiBold, Tahoma;
    margin-right: 20%;
}

.content-service {
    color: rgb(141, 147, 155);
    font-family: NotoSansThai_Regular, Tahoma;
    font-size: 19px;
    margin-left: 20%;
}

.partner {
    color: #8d939b;
    font-family: Poppins_Regular, Tahoma;
    font-size: 18px;
    margin-left: 0;
}

.img-partner {
    max-width: 60%;
    height: auto;
}
.main{
    position: relative;
    background-image: url("https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F05__BG.png?v=202305101549");
    background-repeat: no-repeat;
    background-position-x: 50%;
    background-position-y: 50%
}
</style>