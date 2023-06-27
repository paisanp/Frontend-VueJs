<template>
    <div class="main">
        <h1>ข่าวสาร และบทความ ClickNext</h1>
        <div class="main-container">
            <div class="container">
                <img src="https://blog.clicknext.com/wp-content/uploads/2023/06/CN-Blog6-400x225.jpg?v=202305101549" alt="">
                <div class="content">
                    <p>June 07, 2023 | Nunthaporn.T</p>
                    <h3><a href="">Metaverse คืออะไร ? เทคโนโลยีมาแรงที่ทั่วโลกจับตามอง พร้อมตัวอย่างการใช้งานจริง</a></h3>
                    <p>Metaverse คือ หนึ่งในเทคโนโลยีที่หลาย ๆ สำนัก จัดให้อยู่ในอันดับต้น ๆ
                        ของเทรนด์เทคโนโลยีที่มาแรงแห่งอนาคต เป็นเทคโนโลยี</p>
                    <p><a href="" class="readme">Read more  ></a></p>
                </div>
            </div>

            <div class="container">
                <img src="https://blog.clicknext.com/wp-content/uploads/2023/06/Blog-400x225.png?v=202305101549" alt="">
                <div class="content">
                    <p> June 01, 2023 | Nunthaporn.T</p>
                    <h3><a href="">10 อันดับเทรนด์เทคโนโลยีปี 2023 ที่ต้องรู้ และเตรียมตัวให้พร้อม</a></h3>
                    <p>เทรนด์เทคโนโลยีในแต่ละปีเป็นเรื่องที่น่าตื่นเต้นและน่าสนใจมากๆ
                        ว่าเราจะเห็นเทคโนโลยีก้าวหน้าไปในทิศทางใด จะทำให้การดำเนินชีวิต</p>
                    <p><a href="" class="readme">Read more  ></a></p>
                </div>
            </div>

            <div class="container">
                <img src="https://blog.clicknext.com/wp-content/uploads/2023/05/CN-Blog4_Kotlin-Multiplatform-400x225.png?v=202305101549"
                    alt="">
                <div class="content">
                    <p> May 25, 2023 | First</p>
                    <h3><a href="">Kotlin Multiplatform เขียนโค้ดครั้งเดียวใช้ได้ทั้ง iOS และ Android</a></h3>
                    <p>การพัฒนาแอปพลิเคชันบนมือถือกำลังเป็นที่นิยมอย่างมาก แต่กว่าที่จะพัฒนาแอปพลิเคชันบนมือถือออกมาสำเร็จ 1
                        แอปพลิเคชัน จะต้อง</p>
                    <p><a href="" class="readme">Read more  ></a></p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
h1 {
    text-align: center;
    font-family: Poppins_SemiBold,Tahoma;
    font-size: 40px;
    color: #3b4044;
}
h2{
    font-size: 18px;
}

.main {
    margin: 0 6rem;
}

.main-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
}

.container {
    border: solid 1px #8d939b;
    margin-left: 2rem;
}

.content {
    padding: 1rem;
}

a {
    text-decoration: none;
    color: black
}

a:hover {
    text-decoration: underline;
    color: red
}

p{
    color: #8d939b;
    font-family: NotoSansThai_Regular,Tahoma;
    font-size: 18px;
}

img {
    margin-top: 1.5rem;
}
.readme{
    color:#8d939b;
}

</style>