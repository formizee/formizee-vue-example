<template>
  <form method="post" action="https://api.formizee.com/v1/f/enp_123456">
    <label htmlFor="name">
      Name
      <input id="name" autoComplete="name" name="name" />
    </label>
    <label htmlFor="email">
      Email
      <input id="email" autoComplete="email" name="email" />
    </label>
    <button type="submit">Submit</button>
  </form>
</template>

<style scoped>
  form {
    gap: 2rem;
    width: 100%;
    padding: 8px;
    display: flex;
    max-width: 420px;
    margin-top: 2rem;
    align-items: center;
    flex-direction: column;
    justify-content: center;

    label {
      gap: 0.5rem;
      width: 100%;
      display: flex;
      color: #525252;
      font-size: 0.875rem;
      line-height: 1.25rem;
      flex-direction: column;
    }

    input {
      display: flex;
      height: 2.25rem;
      border-radius: 0.365rem;

      font-size: 0.875rem;
      line-height: 1.25rem;

      background: transparent;

      border: 1px solid #e5e5e5;
      box-shadow: 0 1px 2px 0 rgb(0 0 0 / 0.05);

      transition-property: color, background-color, border-color, text-decoration-color, fill, stroke;
      transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
      transition-duration: 150ms;
    }

    input:focus-visible {
      outline: 2px solid transparent;
      outline-offset: 2px;
      box-shadow: inset 0 0 0 2px #d4d4d4;
    }

    input::placeholder {
      color: #a3a3a3;
    }

    button {
      width: 100%;
      display: flex;
      height: 2.5rem;
      align-items: center;
      justify-content: center;

      border-width: 2px;
      border-color: #404040;
      border-radius: 0.365rem;

      color: #fafafa;
      background-color: #171717;

      font-weight: 600;
      font-family: "Space Grotesk";

      cursor: pointer;
      transition-property: color, background-color, border-color, text-decoration-color, fill, stroke;
      transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
      transition-duration: 150ms;
    }

    button:hover {
      background-color: #262626;
      border-color: #737373;
    }
  }
</style>
