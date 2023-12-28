<script setup>
import Grid from './components/Grid.vue';
import Card from './components/card/Card.vue';
import CardHeader from './components/card/CardHeader.vue';
import CardBody from './components/card/CardBody.vue';
</script>

<template>
  <Grid class="py-5">
    <Card class="col-span-4">
      <CardHeader>
          <h4>Products</h4>
      </CardHeader>
      <CardBody>
        <p>Was geht hier los?</p>
      </CardBody>
    </Card>
    <Card class="col-span-4">
      <CardHeader>
          <h4>Shops</h4>
      </CardHeader>
      <CardBody>
        <p>Was geht hier los?</p>
      </CardBody>
    </Card>
    <Card class="col-span-4">
      <CardHeader>
          <h4>Categories</h4>
      </CardHeader>
      <CardBody>
        <p>Was geht hier los?</p>
      </CardBody>
    </Card>
    <Card class="col-span-4">
      <CardHeader>
          <h4>Offer</h4>
      </CardHeader>
      <CardBody>
        <p>Was geht hier los?</p>
      </CardBody>
    </Card>
    <Card class="col-span-4">Ole</Card>
  </Grid>
</template>

<style scoped>

</style>
