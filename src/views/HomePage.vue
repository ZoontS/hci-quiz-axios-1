<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Home</ion-title>
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Home</ion-title>
        </ion-toolbar>
      </ion-header>
    
      <ion-grid class="ion-no-padding">
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                  <ion-card-title>Kolam</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h1>10</h1>
              </ion-card-content>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                  <ion-card-title>Kolam Aktif</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h1>8</h1>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                  <ion-card-title>Ikan Hidup</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h1>182 Ekor</h1>
              </ion-card-content>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                  <ion-card-title>Ikan Mati</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h1>89 Ekor</h1>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                  <ion-card-title>Panen 2022</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h1>109 Kg</h1>
              </ion-card-content>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                  <ion-card-title>Total Pakan</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h1>223 Kg</h1>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
      <h4 style="margin-left: 20px; font-weight: bold;">TOTAL BERAT IKAN</h4>
      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card>
              <img src="https://png.pngtree.com/png-vector/20220705/ourmid/pngtree-catfish-vector-png-image_5687106.png" />
              <ion-card-header>
                <ion-card-title>LELE</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h2>200 Kg</h2>
              </ion-card-content>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <img src="https://dayyamesin.com/wp-content/uploads/2020/05/nila.png" />
              <ion-card-header>
                <ion-card-title style="margin-top: 26px">NILA MERAH</ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h2>200 Kg</h2>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
      <h4 style="margin-left: 20px; font-weight: bold;">KUALITAS AIR</h4>
      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-title><span style="font-size: 36px; font-weight: bold">pH</span></ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h3>Normal  <span style="color: #2C96F1">6 Kolam</span></h3>
                <h3>Abnormal  <span style="color: #2C96F1">6 Kolam</span></h3>
              </ion-card-content>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-title><span style="font-size: 36px; font-weight: bold">DO</span></ion-card-title>
              </ion-card-header>

              <ion-card-content>
                <h3>Normal  <span style="color: #2C96F1">6 Kolam</span></h3>
                <h3>Abnormal  <span style="color: #2C96F1">6 Kolam</span></h3>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>    
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonCard, IonCardContent, IonCardHeader, IonCardTitle } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
    IonCard,
    IonCardContent,
    IonCardHeader,
    IonCardTitle
  }
});
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins');
* {
  font-family: 'Poppins', sans-serif;
}

h1 {
  font-weight: bold;
}

h2 {
  font-weight: bold;
  color: #2C96F1
}

h3 {
  font-weight: bold;
}

ion-card-title {
  font-weight: bold;
  font-size: 18px;
  --color: #000
}

ion-card {
  --background: #F1F0F2;
  --color: #2E2E2E;
}

ion-title {
  font-weight: bold;
}

#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>
