<template>
  <div id="cv">
      <div class="container">
        <h2>À propos de moi</h2>
        <a class="linkCV" href="http://cv.sarah-majewski.fr/"><img class="card" src="../assets/imageBanner.png" alt=""></a>
      </div>
      <div class="cvContainer">
        <img class="avatar" src="../assets/rond.png" alt="">
        <a class="btn" href="">Téléchargez mon CV</a>
      </div>
    </div>
</template>

<script>
export default {
  name: "CV",
};
</script>
<style scoped>
#cv {
  background-color:#FEFAF6;
  display: flex;
  justify-content: space-around;
  margin:0;
  padding-top:30px;
  padding-bottom:50px;
}
h2 {
  color:#2F3768;
  font-family: 'Bebas Neue';
  font-weight: 300;
  font-size: 30px;
  margin:0px;
  margin-bottom:20px;
}
.btn {
  text-decoration: none;
  background-color: transparent;
  font-size: 20px;
  border: 1px solid #2C2828;
  border-radius: 20px;
  color: #2C2828;
  padding: 8px 15px;
  margin-top: 30px;
}

.btn:hover {
  background-color: #C6D5F0;
  border: 1px solid #C6D5F0;
}
.card{
  border: #9DACD8 2px solid;
  background-color: #DDDFEB;
  border-radius: 20px;
  padding: 10px;
}
img:hover{
  
}
.avatar {
  border-radius:200px;
  height: 140px;
  width: 140px;
  object-fit:cover;
}
.container {
  text-align: center;
  margin:10px;
}

.cvContainer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>