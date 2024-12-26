<template>
  <ion-app>
    <ion-content class="ion-padding">
      <ion-button @click="printPage">Print</ion-button>
    </ion-content>
  </ion-app>
</template>

<script setup lang="ts">
import { IonApp, IonContent, IonButton } from '@ionic/vue';

function printPage() {
  window.print();
}
</script>
