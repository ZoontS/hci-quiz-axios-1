<template>
    <ion-page>
      <ion-tabs>
        <ion-router-outlet></ion-router-outlet>
        <ion-tab-bar slot="bottom">
          <ion-tab-button tab="home" href="/tabs/home">
            <img src="assets/img/Home.svg" alt="">
          </ion-tab-button>
            
          <ion-tab-button tab="kolam" href="/tabs/kolam">
            <img src="assets/img/Kolam.svg" alt="">
          </ion-tab-button>
        </ion-tab-bar>
      </ion-tabs>
    </ion-page>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import { IonTabBar, IonTabButton, IonTabs, IonPage, IonRouterOutlet } from '@ionic/vue';
  import { ellipse, square, triangle } from 'ionicons/icons';
  
  export default defineComponent({
    name: 'TabsPage',
    components: { IonTabs, IonTabBar, IonTabButton, IonPage, IonRouterOutlet },
    setup() {
      return {
        ellipse, 
        square, 
        triangle,
      }
    }
  });
  </script>