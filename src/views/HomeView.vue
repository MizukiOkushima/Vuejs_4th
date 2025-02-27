<template>

  <!-- <SaleGraph /> -->

  <v-container>
    <v-row>

      <!-- <v-col cols="6">
        <SaleGraph />
      </v-col>
      <v-col cols="6">
        <SaleGraph />
      </v-col>
      <v-col cols="6">
        <SaleGraph />
      </v-col>
      <v-col cols="6">
        <SaleGraph />
      </v-col> -->

      <!-- <v-col cols="8">
        <SaleGraph />
      </v-col>
      <v-col cols="4">
        <SaleGraph />
      </v-col> -->

      <!-- <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col>
      <v-col cols="1">
        <SaleGraph />
      </v-col> -->

      <v-col cols="12" sm="6" md="4" lg="3">
        <SaleGraph />
      </v-col>
      <v-col cols="12" sm="6" md="4" lg="3">
        <SaleGraph />
      </v-col>
      <v-col cols="12" sm="6" md="4" lg="3">
        <SaleGraph />
      </v-col>
      <v-col cols="12" sm="6" md="4" lg="3">
        <SaleGraph />
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
import SaleGraph from '../components/SaleGraph'

export default {
  name: 'HomeView',
  components: {
    SaleGraph,
  },
  mounted() {
    console.log(this.$vuetify.breakpoint)
  }
}
</script>
