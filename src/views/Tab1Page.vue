<template>
  <ion-page>
    <ion-header class="login-page">
      <img class="logo-login" src="../../resources/icons/helpr-logo-icon-md-blanc.svg"/>
      <ion-title class="login-text">Sign in</ion-title>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
      </ion-header>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
} from "@ionic/vue";
import ExploreContainer from "@/components/ExploreContainer.vue";
</script>
