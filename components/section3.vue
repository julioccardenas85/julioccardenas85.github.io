<template>
  <div id="container">
    <div class="section" id="left">
      <p>RAQUETAS</p>
    </div>
    <div class="section" id="center">
      <p>PELOTAS</p>
    </div>
    <div class="section" id="right">
      <p>ACCESORIOS</p>
    </div>
  </div>
</template>

<script>
export default {
name: "SectionThree"
}
</script>

<style scoped>
#container {
  height: 560pt;
  display: flex;
  align-content: stretch;
}
.section {
  flex-grow: 1;
  flex-basis: 33%;
  color: white;
  font-family: Apercu;
  font-weight: bold;
  font-size: 40pt;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}
#left {
  background-image: url('~@/assets/Mask_Group@3x.png');
  background-size: auto 100%;
  background-position: center;
}
#center {
  background-image: url('~@/assets/Mask_Group_2@3x.png');
  background-size: auto 100%;
  background-position: center;
}
#right {
  background-image: url('~@/assets/Mask_Group_3@3x.png');
  background-size: auto 100%;
  background-position: center;
}

@media (max-width: 700px) {
  #container {
    flex-direction: column;
  }
  #left {
    background-image: url('~@/assets/Mask_Group@2x.png');
    background-size: 100% auto;
    background-position: 0% 0%;
  }
  #center {
    background-image: url('~@/assets/Mask_Group_2@2x.png');
    background-size: 100% auto;
  }
  #right {
    background-image: url('~@/assets/Mask_Group_3@2x.png');
    background-size: 100% auto;
    background-position: 0% 90%;
  }
}
@media (max-width: 500px) {
  #left {
    background-image: url('~@/assets/Mask_Group.png');
  }
  #center {
    background-image: url('~@/assets/Mask_Group_2.png');
  }
  #right {
    background-image: url('~@/assets/Mask_Group_3.png');
  }
}
</style>