<template>
  <header>
    <h1>Formizee.</h1>
    <span>+</span>
    <figure>
      <img src="@/assets/vue.svg"
        alt="Vue.js logo"
        height="38"
        width="38"
      />
      <span>Vue.js</span>
    </figure>
  </header>
</template>

<style scoped>
  header {
    gap: 1rem;
    display: flex;
    align-items: center;
    flex-direction: row;

    h1, span {
      font-weight: 700;
    }

    figure {
      flex-direction: row;
      align-items: center;
      display: flex;
      gap: 10px;

      font-size: 25px;
      font-weight: 500;
    }
  }
</style>
