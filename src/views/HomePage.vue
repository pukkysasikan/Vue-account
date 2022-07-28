<template>
  <ion-page>
    <ion-header>
      <ion-toolbar color="tertiary" mode="ios">
        <ion-buttons slot="start">
          <ion-back-button color="primary" style="font-weight: 900; margin-left: 1rem;" icon="arrow-back" default-href="" text="&nbsp;&nbsp;&nbsp;ข้อมูลส่วนตัว">
          </ion-back-button>
        </ion-buttons>
        <ion-title></ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content mode="ios">
      <ion-item class="ion-text-center ion-no-padding shortcut ion-no-margin" color="light" lines="none">
        <ion-label class="ion-no-padding ion-no-margin ion-text-center">
          <ion-avatar color="tertiary" style="margin-top: 20px"
            class="avatar-l center ion-margin-top ion-margin-bottom">
            <img :src="require('../assets/imgs/defaultshop.png')">
          </ion-avatar>
          <ion-label color="medium">
            <h3>เปลี่ยนภาพ</h3>
          </ion-label>
          <ion-label>
            <h2><b>Earn</b></h2>
          </ion-label>
          <ion-label color="medium">
            <h3>#77921</h3>
          </ion-label>
        </ion-label>
      </ion-item>

      <ion-list lines="full" class="ion-no-padding" style="margin-top: 0.5rem;">
        <ion-item-sliding color="danger">
          <ion-item button color="tertiary" class="ion-no-padding" expand="full" type="submit"
            routerLink='/tax-address-list'>
            <ion-grid class="ion-no-padding text-hidden">

              <ion-row class="ion-no-padding ion-align-items-center ion-padding-start ion-padding-vertical">
                <ion-col class="ion-padding-start">
                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="dark">
                        <h2><b>เบอร์โทรและอีเมล</b></h2>
                      </ion-label>
                    </ion-col>
                  </ion-row>
                  <ion-row>
                    <ion-col size="10">
                      <ion-label color="medium">
                        <h3>ใช้ผูกบัญชีของ mana</h3>
                      </ion-label>
                    </ion-col>
                  </ion-row>
                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-item>
        </ion-item-sliding>
        
        <ion-item-sliding color="danger">
          <ion-item button color="tertiary" class="ion-no-padding" expand="full" type="submit"
            routerLink='/tax-address-list'>
            <ion-grid class="ion-no-padding text-hidden">

              <ion-row class="ion-no-padding ion-align-items-center ion-padding-start ion-padding-vertical">
                <ion-col class="ion-padding-start">

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="dark">
                        <h2><b>ความปลอดภัย</b></h2>
                      </ion-label>
                    </ion-col>
                  </ion-row>

                  <ion-row>
                    <ion-col size="10">
                      <ion-label color="medium">
                        <h3>PIN, รักษาความปลอดภัยของเครื่อง</h3>
                      </ion-label>
                    </ion-col>
                  </ion-row>

                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-item>
        </ion-item-sliding>


        <ion-item-sliding color="danger" style="margin-top: 0.5rem;">
          <ion-item button color="tertiary" class="ion-no-padding" expand="full" type="submit"
            routerLink='/tax-address-list'>
            <ion-grid class="ion-no-padding text-hidden">

              <ion-row class="ion-no-padding ion-align-items-center ion-padding-start ion-padding-vertical">
                <ion-col class="ion-padding-start">

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="dark">
                        <h2><b>การยืนยันตัวตน KYC</b></h2>
                      </ion-label>
                    </ion-col>
                  </ion-row>

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="medium">
                        <h3>รายละเอียด</h3>
                      </ion-label>
                    </ion-col>
                  </ion-row>
                </ion-col>

                <ion-col size="4">
                  <ion-label color="danger">
                    <h3 class="ion-text-right">ยังไม่ทำ !</h3>
                  </ion-label>
                </ion-col>

              </ion-row>
            </ion-grid>
          </ion-item>
        </ion-item-sliding>

        <ion-item-sliding color="danger">
          <ion-item button color="tertiary" class="ion-no-padding" expand="full" type="submit"
            routerLink='/tax-address-list'>
            <ion-grid class="ion-no-padding text-hidden">

              <ion-row class="ion-no-padding ion-align-items-center ion-padding-start ion-padding-vertical">
                <ion-col class="ion-padding-start">

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="dark">
                        <h2><b>ข้อมูลส่วนตัว</b></h2>
                      </ion-label>
                    </ion-col>
                  </ion-row>

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="medium">
                        <h3>การอนุญาตให้ใช้ข้อมูลของคุณ</h3>
                      </ion-label>
                    </ion-col>
                  </ion-row>
                </ion-col>

              </ion-row>
            </ion-grid>
          </ion-item>
        </ion-item-sliding>

         <ion-item-sliding color="danger" style="margin-top: 0.5rem;">
          <ion-item button color="tertiary" class="ion-no-padding" expand="full" type="submit"
            routerLink='/tax-address-list'>
            <ion-grid class="ion-no-padding text-hidden">

              <ion-row class="ion-no-padding ion-align-items-center ion-padding-start ion-padding-vertical">
                <ion-col class="ion-padding-start">

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="dark">
                        <h2><b>การส่งของ</b></h2>
                      </ion-label>
                    </ion-col>
                  </ion-row>

                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-item>
        </ion-item-sliding>
        <ion-item-sliding color="danger" style="margin-top: 0.5rem;">
          <ion-item button color="tertiary" class="ion-no-padding" expand="full" type="submit"
            routerLink='/tax-address-list'>
            <ion-grid class="ion-no-padding text-hidden">

              <ion-row class="ion-no-padding ion-align-items-center ion-padding-start ion-padding-vertical">
                <ion-col class="ion-padding-start">

                  <ion-row>
                    <ion-col size="8">
                      <ion-label color="dark">
                        <h2><b>การแจ้งเตือน</b></h2>
                      </ion-label>
                    </ion-col>
                  </ion-row>

                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-item>
        </ion-item-sliding>

      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonContent,
  IonHeader,
  IonPage,
  IonGrid,
  IonItem,
  IonItemSliding,
  IonList,
  IonLabel,
  IonCol,
  IonRow,
  IonTitle,
  IonToolbar,
  IonAvatar,
  IonButtons,
  IonBackButton,

} from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonGrid,
    IonItem,
    IonItemSliding,
    IonList,
    IonLabel,
    IonCol,
    IonRow,
    IonTitle,
    IonToolbar,
    IonAvatar,
    IonButtons,
    IonBackButton,
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
