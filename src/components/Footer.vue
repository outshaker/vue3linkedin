<template>
  <footer class="d-flex">
    <!-- Footer content goes here -->
    <div class="logo mt-4 ms-4">
      <img alt="logo" src="../assets/logo.png" />
    </div>
    <nav d-flex flex-column>
      <!-- 上下兩塊 -->
      <div class="nav_title d-flex mb-5">
        <h6>Navigation</h6>
        <h6></h6>
        <h6></h6>
        <h6>Fast access</h6>
        <h6>Language</h6>
      </div>

      <div>
        <div class="Navigation d-flex">
          <div class="nav_body">
            <p>Home</p>
            <p>About</p>
            <p>Services</p>
            <p>Portfolio</p>
          </div>
          <div class="nav_body">
            <p>Talent Solutions</p>
            <p>Marketing Solutions</p>
            <p>Sales Solutions</p>
            <p>Safery Center</p>
          </div>
          <div class="nav_body">
            <p>Community Guidelines</p>
            <p>Privacy & Terms </p>
            <p>Mobile App</p>
          </div>

          <div class="fast_access">
            <div class="nav_body">
              <div class="questions">
                <a class="me-4">Questions?</a>
                <img src="../assets/bell.png" alt="Questions">
              </div>
            </div>
            <div class="nav_body mt-3">
              <div class="settings">
                <a class="me-4">Settings?</a>
                <img src="../assets/bell.png" alt="Settings">
              </div>
            </div>
          </div>

          <div class="language">
            <div class="nav_body">
              <select name="" id="">
                <option value="en">English</option>
                <option value="zh">中文</option>
                <option value="jp">日本語</option>
              </select>
            </div>
          </div>
        </div>
        
        
      </div>
    </nav>
  </footer>
</template>

<script>

export default {
  name: "Footer",
  // Component logic goes here
};
</script>

<style scoped>
footer {
  margin-left: 130px;
  margin-right: 130px;
}

.nav_title h6 {
  width: 160px;
  font-weight: 800;
}

.nav_title h6:nth-child(2) {
  background: firebrick;
}

.nav_title h6:nth-child(3) {
  background: sandybrown;
}

.nav_title h6:nth-child(5) {
  margin-left: 30px;
} 

.Navigation .nav_body {
  width: 160px;
}

.Navigation .nav_body:nth-child(2) {

}


.fast_access {
  margin-left: 50px;
}

.language {
  
}

.questions, .settings {
  border: 1px solid #000;
  padding: 5px 10px;
  border-radius: 5px;
}

.fast_access .nav_body {
  background-color:  #fff;
  color: #0275B1;
  width: 170px;
}

.fast_access .nav_body a {
  text-decoration: none;
}

/* 滑過時的樣式 */ /* 點擊時的樣式 */
.fast_access .nav_body:hover,
.fast_access .nav_body:active {
  background-color: #0275B1; 
  color: #fff; 
}

.language select {
  width: 270px;
  height: 36px;
  border-radius: 5px;
  margin-left: 40px;
}
/* Component styles go here */
</style>