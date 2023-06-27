<template>
    <h1>LOCATIONS</h1>
    <div class="grid">
        <div>
            <h2>BangKok, TH</h2>
            <p>128/323-333 30th FL. Phayathai</p>
            <p>Plaza Bldg. Phayathai road,</p>
            <p>Thung Phayathai, Ratchathewi,</p>
            <p>Bangkok, 10400, Thailand.</p>
            <br>
            <p><a href="">+66-2217-7900</a></p>
        </div>

        <div>
            <h2>Chonburi, TH</h2>
            <p>เลขที่ 22/14-15 ถนนบางแสนสาย 4 เหนือ</p>
            <p>ตำบลแสนสุข อำเภอเมืองชลบุรี จังหวัดชลบุรี 20130</p>
            <br>
            <p><a href="">+66-2217-7900</a></p>
        </div>

        <div>
            <h2>Jakarta, ID</h2>
            <p>PT Klik Digital Nusantara AXA Tower</p>
            <p>Lantai 36, Kuningan City Jl. Prof. Dr.</p>
            <p>Satrio Kav. 18 Jakarta Selatan 12940</p>
            <br>
            <p><a href="">+62-8111-9080-89</a></p>
        </div>
    </div>
    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F11_Slide.png?v=202305101549" alt="">
</template>

<style scoped>

h1 {
    margin-top: 4rem;
    margin-bottom: 2rem;
    text-align: center;
    font-family: Poppins_SemiBold, Tahoma;
    font-size: 40px;
    color:#212121;
}
h2 {
    color:#e1032b;
    font-size: 24px;
    font-family: Poppins_SemiBold, Tahoma;
}

p {
    color:#8d939b;
    font-size: 18px;
}
.grid {
    margin-bottom: 3rem;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    padding: 0 8rem;
}

img {
    width: 100%;
    height: auto;
}

a {
    color:#8d939b;
    text-decoration: none;
}

a:hover {
    color:red;
    text-decoration: underline;
}
</style>