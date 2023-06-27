<template>
    <div class="main">
        <div class="img">
            <img src="https://image.makewebeasy.net/makeweb/m_200x200/m14BHwk4P/Home/clicknext_logo2x.png?v=202305101549" alt="">
        </div>
        <div class="navbar">
            <ul>
                <li><a href="">HOME</a></li>
                <li class="solution-dropdown"><a href="">SOLUTION
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M16.293 9.293 12 13.586 7.707 9.293l-1.414 1.414L12 16.414l5.707-5.707z"></path></svg>
                    </a>
                    <div class="solution-dropdown-content">
                        <div class="solution-item-drop"><a href="" style="color: #9b9b9b;">MARKETING PLATFORM &nbsp; >
    
                        </a> 
                            <div class="solution-item-drop-content"> 
                                <p><a href="" style="color: #9b9b9b;">SMSMKT</a></p>
                                <p><a href="" style="color: #9b9b9b;">MakeWebEasy</a></p>
                                <p><a href="" style="color: #9b9b9b;">Chatcone</a></p>
                                <p><a href="" style="color: #9b9b9b;">Line OA Customization</a></p>
                            </div> 
                        </div>
                        <div class="solution-item-drop"><a href="" style="color: #9b9b9b;">ENTERPRISE SOFTWARE</a></div>
                        <div class="solution-item-drop"><a href="" style="color: #9b9b9b;">SOFTWARE DEVELOPMENT</a></div>
                        <div class="solution-item-drop"><a href="" style="color: #9b9b9b;">ENTERPRISE SOLUTION</a></div>
                        <div class="solution-item-drop"><a href="" style="color: #9b9b9b;">IT SULOTION</a></div>
                    </div>
                </li>
                <li><a href="">SUCCESS STORY</a></li>
                <li><a href="">BLOG</a></li>
                <li class="more-dropdown"><a href="">เพิ่มเติม<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M16.293 9.293 12 13.586 7.707 9.293l-1.414 1.414L12 16.414l5.707-5.707z"></path></svg></a>
                    <div class="more-dropdown-content">
                        <div class="more-item-drop"><a href="" style="color: #9b9b9b;"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M13.293 6.293 7.586 12l5.707 5.707 1.414-1.414L10.414 12l4.293-4.293z"></path></svg>CAREER</a> 
                            <div class="more-item-drop-content"> 
                                <p><a href="" style="color: #9b9b9b;">Full-time jobs</a></p>
                                <p><a href="" style="color: #9b9b9b;">Internship</a></p>
                            </div> 
                        </div>
                        <div class="more-item-drop"><a href="" style="color: #9b9b9b;"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M13.293 6.293 7.586 12l5.707 5.707 1.414-1.414L10.414 12l4.293-4.293z"></path></svg>COMPANY</a></div>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
.main {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-left: 10%;
    padding-right: 10%;
}

.navbar ul{
    display: flex;
    text-align: center;
}

ul > li {
    margin: 1rem;
    list-style-type: none;
    font-family: Kanit_Light0;
    font-size: 18px;
    
}

img {
    width: 192px;
    height: 72px;
}
a{
    color: black;
    text-decoration: none;
    padding-bottom: 1rem;
}
a:hover{
    color: #ed3e4b !important;
    padding-bottom: 1rem;
}
.solution-dropdown {
  position: relative;
  display: inline-block;
  text-align: left;
}

.solution-dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 270px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  margin-top: 10px;
  margin-left: -20px;
}

.solution-dropdown:hover .solution-dropdown-content {
  display: block;
}
.solution-item-drop {
  position: relative;
  display: inline-block;
  text-align: left;
    padding-left: 0.5em;
    margin: 0.5rem;
    
}

.solution-item-drop-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 200px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  margin-top: -30px;
  margin-left: 230px;
  padding: 0 1em;
}
.solution-item-drop:hover .solution-item-drop-content {
  display: block;
}

/* more */
.more-dropdown {
  position: relative;
  display: inline-block;
  text-align: left;
}

.more-dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 140px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  margin-top: 10px;
  margin-left: -20px;

}

.more-dropdown:hover .more-dropdown-content {
  display: block;
}
.more-item-drop {
  position: relative;
  display: inline-block;
  margin-bottom: 10px;
  padding-left: 10px;
}

.more-item-drop-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 120px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  margin-top: -30px;
  margin-left: -145px;
  padding-left: 1em;
}
.more-item-drop:hover .more-item-drop-content {
  display: block;
}
</style>