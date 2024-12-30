<template>
  <footer>
    <div>
      <a
        href="https://docs.formizee.com"
        target="_blank"
        rel="noopener noreferrer"
      >
        <img
          aria-hidden
          src="@/assets/file.svg"
          alt="File icon"
          width="16"
          height="16"
        />
        Learn
      </a>
      <a
        href="https://docs.formizee.com/docs/quickstart"
        target="_blank"
        rel="noopener noreferrer"
      >
        <img
          aria-hidden
          src="@/assets/window.svg"
          alt="Window icon"
          width="16"
          height="16"
        />
        Examples
      </a>
      <a
        href="https://formizee.com"
        target="_blank"
        rel="noopener noreferrer"
      >
        <img
          aria-hidden
          src="@/assets/globe.svg"
          alt="Globe icon"
          width="16"
          height="16"
        />
        formizee.com
      </a>
    </div>
  </footer>
</template>

<style scoped>
  footer {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    margin-top: 2rem;
    padding: 8px;

    div {
      display: flex;
      flex-direction: row;
      gap: 2rem;
    }

    a {
      gap: 1rem;
      color: black;
      display: flex;
      align-items: center;
      text-decoration: none;
      font-family: 'Space Grotesk'
    }
    a:hover {
      text-decoration: underline;
      text-underline-offset: 4px;
    }
  }
</style>
