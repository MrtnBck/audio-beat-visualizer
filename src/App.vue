<template>
  <section>
    <div class="circle"></div>
  </section>
</template>

<script>
export default {
  setup() {},
};
</script>

<style>
body {
  margin: 0;
}

section {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 100vh;
  background: linear-gradient(0deg, #485563, #29323c);
}

section .circle {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  background: linear-gradient(0deg, #fe8c00, #f83600);
  box-shadow: 0px 0px 30px #0f1316;
}
</style>
