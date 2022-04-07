<template>
  <div id="bannerHome">
        <div class="textBanner">
            <h2> SARAH MAJEWSKI</h2>
            <p>Développeur Web FullStack</p>
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
    background-image:url(../assets/fond_portfolio.png) ;
    position: absolute;
    top:100px;
    width: 100%;
    height: 450px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}

img {
    width:350px;
    margin-right: 150px;
}

h2 {
    font-size: 40px;
}
p {
    font-family: 'Bebas Neue';
    font-size: 30px;
    color: #2F3768;
}
</style>