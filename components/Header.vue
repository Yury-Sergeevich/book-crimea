<template>
  <header class="header">
    <div class="topContainer">
      <ul class="userNavList list">
        <li class="userNavItem">
          <button class="button">
            <span class="buttonTitle">Поиск</span>
          </button>
        </li>
        <li class="userNavItem">
          <button class="button" type="button">
            <span class="buttonTitle">Вход</span>
          </button>
        </li>
      </ul>
    </div>
    <hr class="line" />
    <h1>Крымский Калейдоскоп</h1>
    <Nav />
  </header>
</template>

<script setup></script>

<style lang="scss">
.header {
  width: 100%;
}

.userNavList {
  display: flex;
}

.input {
  border: none;
}
</style>
