<template>
  <div class="admin-menu">
    <h1 class="pretty-font">User Menu</h1>

    <div class="menu-options">
      <router-link class="action-button" to="/accounts">Account Management Portal</router-link>
      <router-link class="action-button" to="/transactions">View Transactions</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'UserMenu',
};
</script>

<style scoped>
.admin-menu {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: rgb(214, 192, 255); /* Baby Pink Background */
  /* Add the following line to set the background image */
  background-image: url('../../images/I.jpg'); /* Replace 'path/to/your/image.jpg' with the actual path to your image file */
  background-size: cover; /* Adjust the size of the background image */
}

.menu-options {
  display: flex;
  flex-direction: column;
  gap: 20px;
  text-align: center;
}

.pretty-font {
  font-family: 'Cursive', sans-serif; /* Choose an appropriate pretty font */
  font-size: 3rem;
  color: #fff; /* White Text Color */
}

.action-button {
  text-decoration: none;
  color: #fff; /* White Text Color */
  background-color: #ff69b47f; /* Hot Pink Button Color */
  padding: 10px 20px;
  font-size: 1.2rem;
  border-radius: 5px;
  cursor: pointer;
}

.action-button:hover {
  background-color: #ff69b4;
}
</style>
