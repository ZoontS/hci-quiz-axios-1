<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Kolam<img style="height: 22px; margin-bottom: -3px; margin-left: 60%;" src="assets/img/kolam/Sorting.svg"><img style="margin-left: 20px;" src="assets/img/kolam/Vector.svg"></ion-title>     
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Kolam</ion-title>
        </ion-toolbar>
      </ion-header>
    
      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-content>
                <div class="card-head">
                  <h1>Alpha</h1>
                  <button class="kolam-aktif">Aktif</button>
                </div>
                <hr>
                <div class="card-body">
                  <img src="assets/img/kolam/Calendar Plus.svg">
                  <p>01-09-2022</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Timesheet.svg">
                  <p>90 Hari</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Whole Fish.svg">
                  <p>200 Ekor</p>
                </div>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-content>
                <div class="card-head">
                  <h1>Beta</h1>
                  <button class="kolam-tidak-aktif">Tidak Aktif</button>
                </div>
                <hr>
                <div class="card-body">
                  <img src="assets/img/kolam/Calendar Plus.svg">
                  <p>01-09-2022</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Timesheet.svg">
                  <p>90 Hari</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Whole Fish.svg">
                  <p>200 Ekor</p>
                </div>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-content>
                <div class="card-head">
                  <h1>Gamma</h1>
                  <button class="kolam-aktif">Aktif</button>
                </div>
                <hr>
                <div class="card-body">
                  <img src="assets/img/kolam/Calendar Plus.svg">
                  <p>01-09-2022</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Timesheet.svg">
                  <p>90 Hari</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Whole Fish.svg">
                  <p>200 Ekor</p>
                </div>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-content>
                <div class="card-head">
                  <h1>Delta</h1>
                  <button class="kolam-aktif">Aktif</button>
                </div>
                <hr>
                <div class="card-body">
                  <img src="assets/img/kolam/Calendar Plus.svg">
                  <p>01-09-2022</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Timesheet.svg">
                  <p>90 Hari</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Whole Fish.svg">
                  <p>200 Ekor</p>
                </div>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-content>
                <div class="card-head">
                  <h1>Epsilon</h1>
                  <button class="kolam-aktif">Aktif</button>
                </div>
                <hr>
                <div class="card-body">
                  <img src="assets/img/kolam/Calendar Plus.svg">
                  <p>01-09-2022</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Timesheet.svg">
                  <p>90 Hari</p>
                </div>
                <div class="card-body">
                  <img src="assets/img/kolam/Whole Fish.svg">
                  <p>200 Ekor</p>
                </div>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageSecond',
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar
  }
});
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins');
* {
  font-family: 'Poppins', sans-serif;
}

hr {
  margin-top: 10px;
  border-bottom: 2px solid;
}

h1 {
  font-size: 18px;
  font-weight: bold;
  margin-top: 7px;
  margin-bottom: 0px;
}

.card-head {
  display: flex;
  justify-content: space-between;
}

.kolam-aktif {
  justify-content: center;
  align-items: center;
  padding: 5px 10px;
  gap: 10px;
  width: 58px;
  height: 34px;
  background: green;
  border-radius: 12px;
  font-size: 16px;
  font-weight: bold;
}

.kolam-tidak-aktif {
  justify-content: center;
  align-items: center;
  padding: 5px 10px;
  gap: 10px;
  width: 108px;
  height: 34px;
  background: darkred;
  border-radius: 12px;
  font-size: 16px;
  font-weight: bold;
}

.card-body {
  gap: 7px;
  display: flex;
  align-items: center;
}

ion-card {
  border-radius: 16px;
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
