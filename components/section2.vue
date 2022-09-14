<template>
  <div class="container">
    <div class="products">
      <div class="itemBox">
        <div class="circle">
          <img id="leftArrow" src="~@/assets/Vector_3.png" srcset="~@/assets/Vector_3@2x.png, ~@/assets/Vector_3@3x.png">
        </div>
      </div>
      <div class="itemBox">
        <img class="item" src="~@/assets/Mask_Group_6.png" srcset="~@/assets/Mask_Group_6@2x.png, ~@/assets/Mask_Group_6@3x.png">
        <p class="title">Wilson Championship Extra Duty<br/>Tennis Balls, 3-pk</p>
        <p class="price">$22.09</p>
      </div>
      <div class="itemBox">
        <img class="item" src="~@/assets/Mask_Group_7.png" srcset="~@/assets/Mask_Group_7@2x.png, ~@/assets/Mask_Group_7@3x.png">
        <p class="title">Wilson Starter 3 Balls</p>
        <p style="color: white">.</p>
        <p class="price">$24.69</p>
      </div>
      <div class="itemBox">
        <img class="item" src="~@/assets/Mask_Group_8.png" srcset="~@/assets/Mask_Group_8@2x.png, ~@/assets/Mask_Group_8@3x.png">
        <p class="title">Wilson Tour Slam Lite Tennis<br/>Racquet</p>
        <div class="price"><p>$24.95</p></div>
      </div>
      <div class="itemBox">
        <div class="circle">
          <img id="rightArrow" src="~@/assets/Vector_3.png" srcset="~@/assets/Vector_3@2x.png, ~@/assets/Vector_3@3x.png">
        </div>
      </div>
    </div>
    <div id="button">
      <p>COMPRAR AHORA</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionTwo"
}
</script>

<style scoped>
.container {
  height: 800pt;
  display: flex;
  flex-direction: column;
}
.products {
  height: 440pt;
  display: flex;
  margin-top: 110pt;
}
.itemBox {
  flex-grow: 1;
  display: flex;
  flex-direction: column;
  align-content: space-between;
}
.item {
  max-width: 305pt;
}
.title {
  font-size: 19pt;
  font-family: Apercu;
}
.price {
  font-size: 17pt;
  font-family: Apercu;
  color: rgb(217 99 33);
  margin-top: auto;
}
.circle {
  width: 47.3pt;
  height: 47.3pt;
  background-color: rgb(217 99 33);
  border-radius: 50pt;
  margin: auto;
  display: flex;
  justify-content: center;
}
#leftArrow {
  margin-top: auto;
  margin-bottom: auto;
  width: 7.1pt;
}
#rightArrow {
  margin-top: auto;
  margin-bottom: auto;
  width: 7.1pt;
  transform: scaleX(-1);
}
#button {
  background-color: rgb(217 99 33);
  width: 272pt;
  margin-right: auto;
  margin-left: auto;
  margin-top: 100pt;
  border-radius: 50pt;
  font-size: 15pt;
  color: white;
  font-weight: bold;
  font-family: Apercu;
}

@media (max-width: 700px) {
  .item {
    max-width: 100%;
    height: auto;
    margin-left: auto;
    margin-right: auto;
  }
  .title {
    font-size: 12pt;
  }
  .price {
    font-size: 10pt;
  }
  .products {
    height: auto;
  }
  .container {
    height: auto;
  }
  #button {
    margin-bottom: 110pt;
  }
}

@media (max-width: 500px) {
  .item {
    max-width: 100%;
    height: auto;
    margin-left: auto;
    margin-right: auto;
  }
  .title {
    font-size: 12pt;
  }
  .price {
    font-size: 10pt;
  }
  .products {
    height: auto;
  }
  .container {
    height: auto;
  }
  #button {
    margin-bottom: 110pt;
  }
}
</style>