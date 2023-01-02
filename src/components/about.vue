<template>
  <div id="aboutInfo">
    <div class="taxiAnim">
      <h1 class="findingTaxi">Find Your Personal Taxi <br />With <span>iTaxi</span></h1>
        <h2>We are team of talented talented taxi drivers, <br> making life quick with iTaxi</h2>
        <button id="get-started-btn" class="btn btn-primary">Get Started</button>
    </div>
        <img src="~@/assets/img/hero-img.png" />  
  </div>
</template>
<style>

#aboutInfo {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 20px;
    padding-left: 105px;
    padding-right: 105px;
}

#aboutInfo img {
    padding-top: 40px;
    width: 40%;
}

.findingTaxi {
  color: rgba(255, 255, 255, 0.8);
  font-size: 48px;
  font-weight: 700;
  letter-spacing: 0.5px;
  margin-bottom: 22px;
  font-family: "Montserrat", sans-serif;
}

.taxiAnim h2 {
    color: rgba(255, 255, 255, 0.8);    
    margin-bottom: 40px;
    font-size: 29px;
    font-family: "Montserrat", sans-serif;
    line-height: 1.2;
}

#get-started-btn {
  background: #1ACC8D;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: 550;
  letter-spacing: 1px;
  font-size: 17px;
  display: inline-block;
  padding: 10px 30px;
  border-radius: 50px;
  transition: 0.3s;
  border: none;
  color: #fff;
}

#get-started-btn:hover {
  background:  #14a572;;
}

.logoFind {
  color: #fff;
  font-family: "Montserrat", sans-serif;
}

.taxiAnim span {
  color: #fff;
  border-bottom: 4px solid #1acc8d;
}
</style>
