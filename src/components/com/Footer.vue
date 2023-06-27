<template>
    <div class="main">
        <div class="main-container">
            <div class="">
                <h4>CLICKNEXT COMPANY LIMITED</h4>
                <p>128/323-333 30th FL. Phayathai</p>
                <p>Plaza Bldg. Phayathai road, Thung </p>
                <p>Phayathai, Ratchathewi, Bangkok, </p>
                <p>10400,Thailand.</p>
                <br>
                <p>Phone : <a href="">+66-2217-7900</a></p>
                <p>E-mail : <a href="">info@clicknext.com</a></p>
                <br>
                <div class="social">
                    <p>Social </p>
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/12__icn1.png?v=202012190947" alt="">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/12__icn2.png?v=202012190947" alt="">
                    <img src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home/12__icn3.png?v=202012190947" alt="">
                </div>
                
            </div>

            <div class="container">
                <h4>Company</h4>
                <p><a href="">Team</a></p>
                <p><a href="">Carees</a></p>
                <p><a href="">Success Story</a></p>
                <p><a href="">Contact</a></p>
            </div>

            <div class="container">
                <h4>Service</h4>
                <p><a href="">Software Development</a></p>
                <p><a href="">Mobile Application</a></p>
                <p><a href="">Interactive Media</a></p>
                <p></p>
            </div>

            <div class="container">
                <h4>Products</h4>
                <p><a href="">MakeWebEasy</a></p>
                <p><a href="">ChatCone</a></p>
                <p><a href="">SMS Marketing</a></p>
                <p><a href="">CMS</a></p>
                
                <br>
                <h4>Become to ClickNexter</h4>
                <input type="submit" value="Join us">
            </div>
        </div>
        <p>Copyright © ClickNext Co.,Ltd All right reserved.</p>
    </div>
</template>

<style scoped>
.main {
    background-color: #212529;
    color: aliceblue;
    padding: 3rem 0rem 1rem 5rem;
    color: #8d939b
}

.main-container {
    margin-bottom: 3rem;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
}

.container {
    text-align: center;
}
.social {
    display: flex;
    gap: 20px;
}

a {
    text-decoration: none;
    color: #8d939b
}
a:hover {
    text-decoration: underline;
    color: red
}

h4 {
    color:#ececec
}

input {
    background-color: red;
    font-size: 20px;
    color: #fff;
    border: none;
    padding: 16px 48px;
    border-radius: 25px;
    font-weight: bold;
}
img {
    width: 30px;
    height: 25px;
    margin-top: 1rem;
}
</style>