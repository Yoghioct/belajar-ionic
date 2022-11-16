<template>
    <ion-page>
      <ion-header :translucent="true">
        <ion-toolbar>
          <ion-buttons slot="start">
            <ion-menu-button color="primary"></ion-menu-button>
          </ion-buttons>
          <ion-title>MashkaApp</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-content :fullscreen="true">
        <!-- <div id="container"> -->
            <!-- <ion-grid :fixed="true"> -->
                <ion-row>
                  <ion-col >
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:75px;"/>
                      </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:75px;"/>
                      </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>   
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:75px;"/>
                      </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:75px;"/>
                      </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:75px;"/>
                      </ion-card>
                  </ion-col>
                </ion-row>
              <!-- </ion-grid> -->
            <ion-grid :fixed="true">
                <ion-row>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:100px;"/>
                      </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:100px;"/>
                      </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card>
                        <ion-card-header>
                          <ion-card-title>Cat</ion-card-title>
                        </ion-card-header>
                        <img alt="#" src="https://www.freeiconspng.com/thumbs/cat-png/cat-png-17.png" style="width:auto; height:100px;"/>
                      </ion-card>
                  </ion-col>
                </ion-row>
            </ion-grid>
        <!-- </div> -->
      </ion-content>
    </ion-page>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import { IonButtons, IonContent, IonHeader, IonMenuButton, IonPage, IonTitle, IonToolbar, IonCol, IonGrid, IonRow } from '@ionic/vue';
  
  export default defineComponent({
    name: 'FolderPage',
    components: {
      IonButtons,
      IonContent,
      IonHeader,
      IonMenuButton,
      IonPage,
      IonTitle,
      IonToolbar
    }
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
  