<template>
  <header>
        <div class="containerHeader">
            <div class="logo">
                <h1> Sarah Majewski</h1>
            </div>
            <nav>
                <ul>
                    <a href="#"><li>Accueil</li></a>
                    <a href="#projets"><li>Projets</li></a>
                    <a href="#contact"><li>Contact</li></a>
                    <a href="#cv"><li>CV</li></a>
                </ul>
            </nav>
        </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  position: fixed; 
  top: 0;
  width: 100%;
  font-family: 'Bebas Neue';
  height: 80px;

}
.containerHeader{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
      height: 100px;

}
h1 {
  font-weight: 300;
  font-size: 40px;
  margin-left: 50px;
}
nav {
  font-size: 40px;
  margin-right: 50px;
}
ul {
 display: flex;
 list-style: none;
 padding: 0;
}
li{
   padding-left: 10px;
}
a {
    text-decoration: none;
    color:black;
}
a:hover{
  color:#9DACD8;
}
</style>