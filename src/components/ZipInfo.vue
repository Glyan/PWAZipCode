<template>
  <ion-card v-if="info">
      <ion-card-header>
          <ion-card-subtitle>
              
          </ion-card-subtitle>
      </ion-card-header>
  </ion-card>
</template>

<script>
export default {
    name: "ZipInfo",
    props: ["info"]
}
</script>
