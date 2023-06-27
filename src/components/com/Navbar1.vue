<template>
    <nav>
        <div class="container">
            <div class="nav-wrapper">
                <div class="logo"><img
                        src="https://image.makewebeasy.net/makeweb/m_200x200/m14BHwk4P/Home/clicknext_logo2x.png?v=202305101549"
                        alt=""></div>
                <div class="menu" id="myMenu">
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">SOLUTION</a></li>
                    <li><a href="#">SUCCESS STORY</a></li>
                    <li><a href="#">BLOG</a></li>
                    <li><a href="#">เพิ่มเติม</a></li>
                </div>
                <div class="ham-menu" @click="toggleHam(this)">
                    <div class="bar1"></div>
                    <div class="bar2"></div>
                    <div class="bar3"></div>
                </div>
            </div>
        </div>
    </nav>
</template>

<style scoped>
.container {
    max-width: 1140px;
    margin: 0 auto;
}

nav {
    background-color: #fff;
}

.nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

img {
    width: 192px;
    height: 72px;
}

.menu {
    display: flex;
    list-style: none;
}

.menu li {
    margin-left: 20px;
}

.menu li a {
    text-decoration: none;
}

@media only screen and (max-width: 1020px) {
    .menu {
        display: none;
    }

    .nav-wrapper {
        padding: 1rem;
    }
}

/* Ham */
.ham-menu {
  display: inline-block;
  cursor: pointer;
}

.bar1, .bar2, .bar3 {
  width: 35px;
  height: 5px;
  background-color: #333;
  margin: 6px 0;
  transition: 0.4s;
}

/* Rotate first bar */
.change .bar1 {
  transform: translate(0, 11px) rotate(-45deg);
}

/* Fade out the second bar */
.change .bar2 {opacity: 0;}

/* Rotate last bar */
.change .bar3 {
  transform: translate(0, -11px) rotate(45deg);
}
</style>

<script>
const toggleHam = (x) => {
  x.classList.toggle("change");
}
</script>