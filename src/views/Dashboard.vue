<template>
  <div>
    <h1>Dashboard</h1>
    <template>
      <v-data-table
        :headers="headers"
        :items="desserts"
        :items-per-page="5"
        class="elevation-1"
      ></v-data-table>
    </template>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
