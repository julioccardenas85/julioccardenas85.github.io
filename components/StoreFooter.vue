<template>
  <div id="container">
    <div class="section"></div>
    <div class="section">
      <div>
        <img class="instagram" src="~@/assets/Group_226.png" srcset="~@/assets/Group_226@2x.png, ~@/assets/Group_226@3x.png">
        <img class="facebook" src="~@/assets/Page-1.png" srcset="~@/assets/Page-1@2x.png, ~@/assets/Page-1@3x.png">
      </div>
      <div id="copyright">© DEV. All Rights Reserved. <span style="text-decoration: underline;">Privacy Policy,</span> <span style="text-decoration: underline;">Terms & Conditions</span></div>
    </div>
    <div class="section">
      <img id="ball" src="~@/assets/Group_2.png" srcset="~@/assets/Group_2@2x.png, ~@/assets/Group_2@3x.png">
    </div>
  </div>
</template>

<script>
export default {
name: "StoreFooter"
}
</script>

<style scoped>
#container {
  height: 223pt;
  background-color: rgb(207 224 98);
  display: flex;
  align-content: stretch;
}
.section {
  flex-grow: 1;
  flex-basis: 33%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.instagram {
  height: 32pt;
  margin-right: 11pt;
}
.facebook {
  height: 32pt;
  margin-left: 11pt;
}
#copyright {
  font-size: 13pt;
  font-family: Apercu;
  color: rgb(111 126 13);
  margin-top: 25pt;
}
#ball {
  width: 104pt;
  align-self: flex-end;
  margin-right: 74pt;
}

@media (max-width: 700px) {
  #container {
    flex-direction: column;
  }
  #ball {
    margin: auto;
    width: 50pt;
  }
}

</style>