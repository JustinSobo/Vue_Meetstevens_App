<script>
export default {
  data() {
    return {
      myName: 'name'
        }
    }
}
</script>


<template>

  <div class="align-center">
    <img class="profile-image" src="https://avatars.githubusercontent.com/u/37387224?v=4" alt="Profile photo">
    <h1 :class="myName">JUSTIN STEVENS</h1>


    <div class="flex-container">
      <div class="flex-items">
        <a href="https://www.linkedin.com/in/justinsobo/" target="_blank">
          <i class="fa-brands fa-linkedin-in fa-4x"></i>
        </a>
      </div>

      <div class="flex-items">
        <a href="https://github.com/JustinSobo" target="_blank">
          <i class="fa-brands fa-github fa-4x"></i>
        </a>
      </div>

      <div class="flex-items">
        <a href="https://dribbble.com/justinsobo" target="_blank">
          <i class="fa-solid fa-basketball fa-4x"></i>
        </a>
      </div>

      <div class="flex-items">
        <a href="https://www.instagram.com/justinsobo/" target="_blank">
          <i class="fa-brands fa-instagram fa-4x"></i>
        </a>
      </div>
    </div>
  </div>

<div><p>This is a test. Ignore.</p></div>
<div><p>This is a test. Ignore.</p></div>
</template>



<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

@import url('https://fonts.googleapis.com/css2?family=Jost:wght@800&display=swap');
.name {
  font-size: 4rem;
  font-family: 'Jost', sans-serif;
  color: black;
  text-align: center;
  word-wrap: break-word;
}

.align-center {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.bodyBG {
  background-color: #9AECDB;
}

.flex-container {
  justify-content: center;
  display: flex;
  flex-wrap: wrap;
}

.flex-items {
  flex: 25%;
  justify-content: center;
}

a:link, a:visited, a:hover, a:active {
  color: black;
  background-color: transparent;
  text-decoration: none;
}

.profile-image{
  border-radius: 45%;
  height: 10rem;
}
</style>

