<template>
  <div id="contact">
    <div class="container">
      <h2>CONTACT</h2>
      <a class="btn" href="mailto:sarahmajewski.web@gmail.com">Contactez-moi</a>
    </div>
    <div class="container">
      <h2>INFORMATIONS</h2>
      <div class="infoContainer">
        <img src="../assets/email.svg" alt="email">
        <span>sarahmajewski.web@gmail.com</span>
      </div>
      <div class="infoContainer">
        <img src="../assets/phone.svg" alt="téléphone">
        <span>0782900692</span>
      </div>
    </div>
    
  </div>
    <footer>
    <a class="logo" href="https://www.linkedin.com/in/sarah-majewski/"><img src="../assets/linkedin.svg" alt="Lien Linkedin"></a>
    <a class="logo" href="https://github.com/srh-mji"><img src="../assets/github.svg" alt="Lien Linkedin"></a>
    <p>©2022 Sarah Majewski</p>
  </footer>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
#contact {
  background-color: #DDDFEB;
  display: flex;
  justify-content: space-around;
  margin:0;
  padding-top:30px;
  padding-bottom:50px;
}
.container {
  text-align: center;
  margin:10px;
}
.infoContainer {
  display: flex;
  align-items: center;
}
h2 {
  color:#2F3768;
  font-family: 'Bebas Neue';
  font-weight: 300;
  font-size: 30px;
  margin:10px;
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

}
span {
  margin:10px;
}
footer {
  background-color: #DDDFEB;
  text-align: center;
  padding-bottom: 20px;
}
.image {
  height: 150px;
}
.logo {
  padding: 20px;
}
img {
  height: 30px;
}

</style>