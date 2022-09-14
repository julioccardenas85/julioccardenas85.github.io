<template>
  <div class="container">
    <div class="top">
      <div id="left">
        <p class="topText">Productos</p>
        <img id="arrow" src="~@/assets/Vector_2.png" srcset="~@/assets/Vector_2@2x.png, ~@/assets/Vector_2@3x.png">
      </div>
      <div>
        <img id="player" src="~@/assets/Group.png" srcset="~@/assets/Group@2x.png, ~@/assets/Group@3x.png">
      </div>
      <div>
        <p class="topText" id="right">Contacto</p>
      </div>
    </div>
    <div id="center">
      <div >
        <h1>EL MEJOR DEPORTE</h1>
      </div>
      <div>
        <h2 id="thirdLevel">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</h2>
      </div>
      <div id="fourthLevel">
        <p>COMPRAR AHORA</p>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "SectionOne"
}
</script>

<style scoped>
.container {
  height: 626pt;
  background-image: url('~@/assets/Mask_Group_4@3x.png');
  background-size: auto 100%;
  display: flex;
  flex-direction: column;
  justify-items: flex-start;
}
.top {
  display: flex;
  align-items: start;
  justify-content: space-between;
}
.topText {
  color: white;
  font-size: 15pt;
  font-family: Apercu;
  margin-top: 35pt;
}
#arrow {
  width: 10pt;
  height: 6pt;
  margin-top: 20pt;
  margin-left: 15pt;
}
#left {
  display: flex;
  align-items: center;
  margin-left: 71pt;
  width: 100px;
}
#right {
  margin-right: 71pt;
  width: 100px;
}
#player {
  width: 58pt;
  margin-top: 35pt;
}
h1 {
  color: white;
  font-family: Apercu;
  font-weight: bold;
  font-size: 80pt;
}
h2 {
  color: white;
  font-family: Apercu;
  font-weight: bold;
  font-size: 21pt;
}
#thirdLevel {
  width: 467pt;
  margin-right: auto;
  margin-left: auto;
  margin-top: 1px;
}
#fourthLevel {
  background-color: rgb(217 99 33);
  width: 272pt;
  margin-right: auto;
  margin-left: auto;
  margin-top: 36pt;
  border-radius: 50pt;
  font-size: 15pt;
  color: white;
  font-weight: bold;
  font-family: Apercu;
}
#center {
  display: flex;
  flex-direction: column;
  align-items: center;
}

@media (max-width: 700px) {
  .container {
    background-image: url('~@/assets/Mask_Group_4@2x.png');
    background-size: auto 100%;
    background-position: 75% 100%;
  }
  h1 {
    font-size: 50pt;
  }
}

@media (max-width: 500px) {
  .container {
    background-image: url('~@/assets/Mask_Group_4.png');
    background-size: auto 100%;
    background-position: 75% 100%;
  }
  #left {
    margin-left: 10pt;
  }
  #right {
    margin-right: 10pt;
  }
  h1 {
    font-size: 30pt;
  }
  h2 {
    font-size: 15pt;
  }
  #thirdLevel {
    width: auto;
  }
}
</style>