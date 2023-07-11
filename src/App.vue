<template>
  <div id="app">
    <router-view/>
    <div class="footer">
      <span>© 2023 ALPGO. All Rights Reserved. | <a href="https://beian.miit.gov.cn/" target="_blank">湘ICP备2021021685号-1</a></span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
.footer {
  background-color: #f2f2f2;
  padding: 20px;
  text-align: center;
}

.footer span {
  font-size: 12px;
  color: #777777;
}

.footer a {
  color: #777777;
  text-decoration: none;
}

.footer a:hover {
  text-decoration: underline;
}
</style>
