<script setup>

</script>

<template>
  <div>
    <img src="/src/assets/img/logo_aveyrna_online_story_writer_no_bg.png" class="logo" />
    <p class="desc">Online Story Writer</p>

    <p class="about">Build your story, characters, scenes and more in one place </p>

    <button class="startButton">Start</button>
  </div>
</template>

<style>

body {
  background-color: black;
}

.logo {
  height: 40em;
  will-change: filter;
  transition: filter 300ms;
  margin-top: -250px;
}


.desc {
  color: skyblue;
  font-size: 1.5em;
  margin-top: -110px;
}

.about {
  font-size: 1.6em;
  margin-top: 100px;
}

.startButton {
  margin-top: 50px;
  font-size: 1.7em;
  font-weight: bold;
  color: orchid;
  padding: 10px 20px 10px 20px;
}

.startButton:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

</style>
