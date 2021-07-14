<template>
  <v-row class="fill-height">
      <v-col md="6" class="align-center justify-center d-none d-md-flex backgroundBlue ">
        Monitor GID
      </v-col>
      <v-col sm="12" md="6" class="backgroudWhite align-center justify-center d-flex">
         <FormLogin /> 
      </v-col>
  </v-row>
</template>

<script>

export default {
  layout: 'loginLayout'
}

</script>

<style>
  .backgroundBlue {
    background-color: cornflowerblue;
    color: white;
  }
  .backgroudWhite {
    background-color: #f6f7ff;
  }
</style>>
