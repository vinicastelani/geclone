<template>
  <div class="container d-flex justify-space-between align-center">
    <div class="d-flex align-center">
      <ul class="d-flex">
        <li>globo.com</li>
        <li>g1</li>
        <li>ge</li>
        <li>gshow</li>
        <li>vídeos</li>
      </ul>
    </div>
    <div class="d-flex align-center">
      <img class="user-image" :src="profileImage" alt="User profile picture" />
      <p class="user-name">Vinícius Castelani</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "topnavigationbar",
  computed: {
    profileImage() {
      return require("@/assets/profile.png");
    }
  }
};
</script>

<style scoped>
.user-name {
  font-size: 12px;
  color: #666;
  text-transform: uppercase;
}
.user-image {
  width: 22px;
  height: 22px;
  padding: 0 6px;
}
div {
  min-height: 48px;
}
ul {
  padding: 0;
  margin: 0;
}
li {
  display: flex;
  align-items: center;
  min-height: 48px;
  list-style-type: none;
  font-size: 16px;
  font-weight: bold;
  border-top: 2px solid #f3f3f3;
  padding-top: 2px;
  cursor: pointer;
}
li:nth-child(even) {
  margin: 0 12px;
}

li:nth-child(1) {
  color: #158aff;
}

li:nth-child(2) {
  color: #a80000;
}
li:nth-child(2):hover {
  border-top: solid 2px #a80000;
}

li:nth-child(3) {
  color: #06aa48;
}

li:nth-child(3):hover {
  border-top: solid 2px #06aa48;
}

li:nth-child(4) {
  color: #ff7f00;
}
li:nth-child(4):hover {
  border-top: solid 2px #ff7f00;
}

li:nth-child(5) {
  color: #005cef;
}
li:nth-child(5):hover {
  border-top: solid 2px #005cef;
}
</style>
