<template>
    <div class="main">
        <div class="content">
            <p>Are you ready to</p>
            <p>take your business</p>
            <p>to the next level</p>
            <p>with <strong>CLICKNEXT</strong></p>
        </div>

        <div class="form">
            <input type="text" placeholder="ชื่อ"> <br>
            <input type="text" placeholder="E-mail"> <br>
            <input type="text" placeholder="เบอร์โทรศัพท์"> <br>
            <select name="" id="">
                <option value="">เลือกประเภทการติดต่อ</option>
                <option value="">สมัครงาน / ฝึกงาน</option>
                <option value="">สนใจผลิตภัณฑ์</option>
                <option value="">สนใจบริการ</option>
                <option value="">อื่นๆ</option>
            </select>
            <br>
            <textarea name="ข้อความ" id="" cols="30" rows="5"></textarea>
            
            <br>
            <input type="submit" value="ส่งข้อความ">
        </div>
    </div>
</template>

<style scoped>
.main {
    background-image: url("https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F10_BG_contact_edit_1.jpg?v=202305101549");
    background-color: #cccccc;
    height: auto;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    padding: 5rem 10rem;
}

.content {
    font-size: xx-large;
    color: #fefefe;
    font-family: Poppins_Regular, Tahoma;
}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 15%;
  background-color: red;
  color: white;
  padding: 7px 0px;
  border: none;
  border-radius: 25px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #fff;
  color:red
}
.content p {
    font-size: 36px;
}
</style>