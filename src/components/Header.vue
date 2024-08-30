<script setup lang="ts"></script>

<template>
<div class="header">
  <img class="logo" src="../assets/hacklogo.png">
  <div class="header-right">
    <a href="#">ABOUT</a>
    <a href="#">TRACKS</a>
    <a href="#">SPONSORS</a>
    <a href="#">FAQ</a>
    <a href="#">CONTACT</a>
    <a href="#" class="apply">APPLY</a>
  </div>
  <img class="mobile" src="../assets/hamicon.png">
</div>
</template>

<style scoped>
.header {
  overflow: hidden;
  background-color: #C5D2CE;
  padding: 1.25vw;
  border-bottom: solid 0.25vw black;
  display: flex;
  align-items:center;
}

.header a {
  font-size: 1.5vw;
  font-family: 'pf-videotext';
  color: black;
  text-align: center;
  padding: 1.5vw 2.5vw;
  text-decoration: none;
}

.header img.logo{
  float: left;
  height: 4.5vw;
  width: 4.5vw;
  margin-left:10vw;
  margin-right:15vw;
}

.header a:hover {
  text-decoration: underline;
  transition: ease-in 0.5s;
}

.header a.apply {
  background-color: #64D3F5;
  border: 0.2em solid black;
  margin-left: 1.5vw;
  padding: 1vw 2vw;
}

.header-right {
  float: right;
  display: flex;
  align-items: center;
}

.mobile{
  display: none;
}

@media (max-width: 768px) {
  .header {
    overflow: hidden;
    background-color: #C5D2CE;
    border-bottom: solid 0.75vw black;
    display: flex;
    align-items:center;
  }

  .header a {
    font-size: 5.5vw;
    font-family: 'pf-videotext';
    color: black;
    text-align: center;
    text-decoration: none;
    display: none;
  }

  .header img.logo{
    float: left;
    height: 20vw;
    width: 20vw;
    margin-top: -2vw;
    margin-bottom: -2vw;
    margin-left: 6vw;
    margin-right: 21vw;
  }

  .header a:hover {
    text-decoration: underline;
    transition: ease-in 0.5s;
  }

  .header a.apply {
    background-color: #64D3F5;
    border: .75vw solid black;
    padding: 3.25vw 5vw;
    display: block;
  }

  .header-right {
    float: right;
    display: flex;
    align-items: center;
  }

  .mobile{
    display: block;
    height: 15vw;
    width: 15vw;
    padding-left: 4vw;
    padding-top: 3vw;
  }
}

@media (max-width: 480px) {
  .header {
    overflow: hidden;
    background-color: #C5D2CE;
    border-bottom: solid 0.75vw black;
    display: flex;
    align-items:center;
  }

  .header a {
    font-size: 5.5vw;
    font-family: 'pf-videotext';
    color: black;
    text-align: center;
    text-decoration: none;
    display: none;
  }

  .header img.logo{
    float: left;
    height: 20vw;
    width: 20vw;
    margin-top: -2vw;
    margin-bottom: -2vw;
    margin-left: 6vw;
    margin-right: 21vw;
  }

  .header a:hover {
    text-decoration: underline;
    transition: ease-in 0.5s;
  }

  .header a.apply {
    background-color: #64D3F5;
    border: .75vw solid black;
    padding: 3.25vw 5vw;
    display: block;
  }

  .header-right {
    float: right;
    display: flex;
    align-items: center;
  }

  .mobile{
    display: block;
    height: 15vw;
    width: 15vw;
    padding-left: 4vw;
    padding-top: 3vw;
  }
}
</style>