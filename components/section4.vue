<template>
  <div id="container">
    <h1>DESCUBRE TU PASIÓN</h1>
    <div id="button">
      <p>COMPRAR AHORA</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionFour"
}
</script>

<style scoped>
#container {
  height: 499pt;
  background-image: url('~@/assets/Mask_Group_5@3x.png');
  background-size: auto 100%;
  background-position: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
h1 {
  color: white;
  font-family: Apercu;
  font-weight: bold;
  font-size: 80pt;
}
#button {
  background-color: rgb(217 99 33);
  width: 272pt;
  height: 54pt;
  margin-right: auto;
  margin-left: auto;
  border-radius: 50pt;
  font-size: 15pt;
  color: white;
  font-weight: bold;
  font-family: Apercu;
  display: flex;
  flex-direction: column;
}

@media (max-width: 700px) {
  #container {
    background-image: url('~@/assets/Mask_Group_5@2x.png');
    background-position: 20% 100%;
  }
  h1 {
    font-size: 50pt;
  }
}

@media (max-width: 500px) {
  #container {
    background-image: url('~@/assets/Mask_Group_5.png');
    background-position: 25% 100%;
  }
  h1 {
    font-size: 30pt;
  }
}
</style>