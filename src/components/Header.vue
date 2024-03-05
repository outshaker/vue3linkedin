<template>
  <header class="d-flex">
    <div class="logo mt-4 ms-4">
      <img alt="logo" src="../assets/logo.png" />
    </div>

    <nav class="d-flex">
      <div class="nav_item">
        <div class="navitem__icon"></div>
        <a class="navitem__text" href="##">FREE</a>
      </div>
      <div class="nav_item">
        <div class="navitem__icon"></div>
        <a class="navitem__text" href="##">Network</a>
      </div>
      <div class="nav_item">
        <div class="navitem__icon"></div>
        <a class="navitem__text" href="##">jobs</a>
      </div>
      <div class="nav_item">
        <div class="navitem__icon"></div>
        <a class="navitem__text" href="##">chat</a>
      </div>
      <div class="nav_item">
        <div class="navitem__icon"></div>
        <a class="navitem__text" href="##">notices</a>
      </div>

      <div class="input-group mb-3 ms-5">
        <span class="input-group-text" id="basic-addon1">
          <img src="../assets/search.png" alt="search" />
        </span>
        <input
          type="text"
          class="form-control"
          placeholder="Search"
          aria-label="Username"
          aria-describedby="basic-addon1"
        />
      </div>
    </nav>

    <div class="d-flex mt-4">
      <div>
        <img src="@/assets/rectangle.png" alt="" />
      </div>
      <!-- 左右並排 -->
      <div class="d-flex flex-column">
        <div>
          <p class="name">D. Kargaev</p>
        </div>
        <div class="d-flex">
          <p class="view_quantity">367 views today</p>
          <p class="statistics ms-3">+32</p>
        </div>
      </div>
    </div>

    <div class="d-flex flex-column mt-4 more">
      <img src="@/assets/more.png" alt="" />
      <p class="other">OTHER</p>
    </div>

    <!-- Your header content goes here -->
  </header>
</template>

<script>
export default {
  name: "Header",
  // Your component's logic goes here
};
</script>

<style scoped>
.more {
  width: 24px;
  height: 24px;
}
.other {
  color: #181818;
}
.name {
  color: #181818;
  font-weight: 700;
}

.view_quantity {
  color: #747474;
}

.statistics {
  color: #02b033;
}

.navitem__icon {
  width: 30px;
  height: 20px;
  background-image: url("../assets/rss.png");
  background-repeat: no-repeat;
  background-position: 5px -2px;
  margin: 0 30px;
}
nav .nav_item:nth-child(2) .navitem__icon {
  background-image: url("../assets/users.png");
}
nav .nav_item:nth-child(3) .navitem__icon {
  background-image: url("../assets/briefcase.png");
}
nav .nav_item:nth-child(4) .navitem__icon {
  background-image: url("../assets/message-square.png");
}
nav .nav_item:nth-child(5) .navitem__icon {
  background-image: url("../assets/bell.png");
}
/* Your component's styles go here */
</style>
