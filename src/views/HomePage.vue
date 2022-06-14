<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Corkscrews</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content class="ion-padding">
      <div id="container">
        <ion-icon src="assets/icons/corkscrew.svg"></ion-icon>
        <ion-icon src="assets/icons/corkscrew.svg" color="danger"></ion-icon>
        <ion-icon src="assets/icons/corkscrew.svg" color="primary"></ion-icon>
        <ion-icon src="assets/icons/corkscrew.svg" color="secondary"></ion-icon>
        <ion-icon src="assets/icons/corkscrew.svg" color="tertiary"></ion-icon>
        <ion-icon src="assets/icons/corkscrew.svg" color="warning"></ion-icon>
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonContent,
  IonHeader,
  IonIcon,
  IonPage,
  IonTitle,
  IonToolbar,
} from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomePage",
  components: {
    IonContent,
    IonHeader,
    IonIcon,
    IonPage,
    IonTitle,
    IonToolbar,
  },
});
</script>

<style scoped>
#container {
  text-align: center;

  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

ion-icon {
  font-size: 50px;
}
</style>
