<template>
  <footer class="d-flex">
    <!-- Footer content goes here -->
    <div class="logo mt-4 ms-4">
      <img alt="logo" src="../assets/logo.png" />
    </div>
    <nav d-flex flex-column>
      <!-- 上下兩塊 -->
      <div class="d-flex">
        <h6>Navigation</h6>
        <h6>Navigation2</h6>
        <h6>Navigation3</h6>
      </div>

      <div>
        <div class="Navigation d-flex">
          <div>
            <p>Home</p>
            <p>About</p>
            <p>Services</p>
            <p>Portfolio</p>
          </div>
          <div>
            <p>Blog</p>
            <p>Contact</p>
            <p>Blog</p>
            <p>Contact</p>
          </div>
          <div>
            <p>Blog</p>
            <p>Contact</p>
            <p>Blog</p>
            <p>Contact</p>
          </div>
        </div>
        <div class="Fast_access"></div>
        <div class="Language"></div>
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
/* Component styles go here */
</style>
