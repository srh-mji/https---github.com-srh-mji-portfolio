<template>
  <div id="bannerHome">
      <div class="flex">
        <div>
            <i class="fa-solid fa-cloud"></i>
        <p> Recherche CDI</p>
        <h2> SARAH MAJEWSKI</h2>
        <p>Développeur Web FullStack</p>
      </div>
      <img src="../assets/imageBanner.png" alt=""> 
      </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#bannerHome{
    background-color: #F0CCE8;
    position: absolute;
    top:100px;
    width: 100%;
    height: 500px;
    color: white;
}
.flex {
    display: flex;
}
img {
    width:250px;
}

</style>