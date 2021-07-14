<template>
  <form>
    <h1>Login</h1>
      <v-text-field
        v-model="email"
        label="E-mail"
        required
      ></v-text-field>

      <v-text-field
        v-model="senha"
        label="Senha"
        required
      ></v-text-field>
  </form>
</template>