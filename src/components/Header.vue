<template>
  <header class="app-header" :class="{ 'app-header--ondark': isBaner }">
    <div class="company-logo-container">
      <img src="" alt="metzlom" />
    </div>
    <div class="app-header-nav-container">
      <g-link class="app-header-link" to="/">O nas</g-link>
      <g-link class="app-header-link" to="/Skup">Skup złomu</g-link>
      <g-link class="app-header-link" to="/Wyroby">Wyroby hutnicze</g-link>
      <g-link class="app-header-link" to="/Rozbiorki">Rozbiórki</g-link>
      <g-link class="app-header-link" to="/Kontakt">Kontakt</g-link>
    </div>
    <div class="mail-icon-container">
      <!-- <icon></icon> -->
    </div>
    <div class="translate-icon-container"></div>
  </header>
</template>

<style>
.app-header {
  width: 100%;
  height: 100px;
  background: blue;
  position: fixed;
  top: 0;
  left: 0;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.app-header-link {
  margin-right: 20px;
  text-transform: uppercase;
  color: black;
}

.app-header--ondark {
  background: none;
}

.app-header--ondark .app-header-link {
  color: white;
}
</style>
