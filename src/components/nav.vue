<template>
  <div id="hold">
    <a href="#"><h1>iTaxi</h1></a>

    <div class="linkes">
      <ul>

        <li><a id="homeColor" class="bottomLine" href="#">Home</a></li>
        <li><a class="bottomLine" href="#">About</a></li>
        <li><a class="bottomLine" href="#">Features</a></li>
        <li><a class="bottomLine" href="#">Gallery</a></li>
        <li><a class="bottomLine" href="#">Team</a></li>
        <li><a class="bottomLine" href="#">Pricing</a></li>
        <li><a class="bottomLine" href="#">Drop Down <i class="fas fa-angle-down"></i> </a></li>
        <li><a class="bottomLine" href="#">Contact</a></li>
  
      </ul>
    </div>
    <!--this is the div of hold-->
  </div>
</template>

// .overlayBackground { // z-index: 967; // background: rgba(1, 4, 136, 0.9); // position:
absolute; // left: 0; // top: 0; // bottom: 0; // width: 100%; // height: 100%; // }
<style>
*,
::after,
::before {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  background-color: rgba(1, 4, 136, 0.9);
}

body {
  background-image: url("~@/assets/img/hero-bg.jpg");
  height: 605px;
  width: 100%;
  font-family: "Open Sans", sans-serif;
}

#hold {
  padding-left: 105px;
  padding-right: 105px;
  padding-top: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

#hold a {
  text-decoration: none;
}

#homeColor {
  color: #fff;
  width: 0;
}

#homeColor::after {
  content: "";
  display: block;
  width: 0;
  height: 2px;
  background: #1acc8d;
}

#homeColor::after {
  width: 60%;
}

.linkes li {
  text-decoration: none;
  padding-left: 16px;
  padding-right: 16px;
  font-family: "Poppins", sans-serif;
  font-weight: 600;
  transition: 0.3s;
  list-style: none;
}

.linkes li a:hover {
  color: #fff;
}

.bottomLine::after {
  content: "";
  display: block;
  width: 0;
  height: 2px;
  background: #1acc8d;
  transition: width 0.3s;
}

.bottomLine:hover::after {
  width: 60%;
  transition: width 0.3s;
}

.linkes ul {
  display: flex;
}

.linkes a {
  text-decoration: none;
  color: rgba(255, 255, 255, 0.7);
  transition: 0.3s;
  font-size: 15.9px;
  font-weight: 500;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue",
    Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
    "Segoe UI Symbol", "Noto Color Emoji";
}

#hold h1 {
  color: #fff;
  font-family: "Montserrat", sans-serif;
  font-weight: 700;
  font-size: 30px;
}
</style>
