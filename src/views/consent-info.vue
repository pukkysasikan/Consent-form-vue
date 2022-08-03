<template>
  <ion-page>

    <ion-header>
      <ion-toolbar color="tertiary" mode="ios">
        <ion-buttons slot="start">
          <ion-back-button color="primary" style="font-weight: 900; margin-left: 1rem;" icon="arrow-back"
            default-href="" text="&nbsp;&nbsp;คำขออนุญาตให้คุณเป็นบริษัท Delivery">
          </ion-back-button>
        </ion-buttons>
        <ion-title></ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content mode="ios">
      <ion-card color="tertiary" style="margin-top: 10rem;">
        <div class="ion-text-center ion-padding-top">
          <img class="circle logo-l" :src="require('../assets/imgs/defaultshop.png')" />
        </div>
        <ion-label color="dark">
          <h2 class="ion-margin-top ion-text-center"><b>Devter</b></h2>
        </ion-label>
        <br>
      </ion-card>

      <ion-card class="ion-padding-top">
        <ion-item color="tertiary" lines="none">
          <ion-grid style="padding: 10px 0px 0px 10px;">
            <ion-row>
              <ion-col class="ion-no-padding">
                <ion-text>
                  <ion-label>
                    <h2><b>ขออนุญาตเปิดบริษัท</b></h2>
                  </ion-label>
                </ion-text>
              </ion-col>
              <ion-col class="ion-no-padding ion-text-right">
                <ion-text>
                  <ion-label>
                    <h4>อ่านเพิ่มเติม</h4>
                  </ion-label>
                </ion-text>
              </ion-col>
            </ion-row>
            <ion-text style="font-size: 14px;">
              <b>Devter</b>&nbsp;จะสร้างร้าน<b>&nbsp;DD Delivery</b>&nbsp;โปรดอ่าน และยินยอม
              ข้อตกลงในการทำสัญญาเพื่อใช้งานระบบ
            </ion-text>
          </ion-grid>
        </ion-item>
      </ion-card>

      <ion-card class="ion-padding-top">
        <ion-card color="tertiary" style="padding: 10px 0px 0px 10px;">
          <ion-text>
            <ion-label class="ion-no-padding">
              <h2 style="margin-left: 1rem;"><b>ผู้ใช้งาน</b></h2>
            </ion-label>
          </ion-text>
          <div class="ion-text-center">
            <img class="circle logo-l" :src="require('../assets/imgs/defaultshop.png')" />
          </div>
          <ion-label color="dark">
            <h2 class="ion-margin-top ion-text-center"><b>อานนท์ บางสาน</b></h2>
          </ion-label>
          <br>
        </ion-card>
      </ion-card>

      <ion-card class="ion-padding-top">
        <ion-card color="tertiary" style="padding: 0px 10px 0px 10px;">
          <ion-text>
            <ion-label style="padding: 0px 10px 0px 10px;">
              <h2 style="margin-left: 1rem;"><b>ทำระบบ&nbsp;Escrow&nbsp;ที่มีส่วนแบ่ง</b></h2>
            </ion-label>
          </ion-text>
          <ion-grid style="padding: 0px 10px 0px 10px;">
            <ion-row>
              <ion-col class="ion-padding">
                <ion-text>
                  <ion-label>
                    <h5>Software</h5>
                  </ion-label>
                </ion-text>
              </ion-col>
              <ion-col class="ion-padding ion-text-right">
                <ion-text>
                  <ion-label>
                    <h2><b>10 %</b></h2>
                  </ion-label>
                </ion-text>
              </ion-col>
            </ion-row>
          </ion-grid>
          <ion-grid style="padding: 0px 10px 0px 10px;">
            <ion-row>
              <ion-col class="ion-padding ">
                <ion-text>
                  <ion-label>
                    <h5>Rider</h5>
                  </ion-label>
                </ion-text>
              </ion-col>
              <ion-col class="ion-padding ion-text-right">
                <ion-text>
                  <ion-label>
                    <h2><b>50<small>THB</small>&nbsp;+&nbsp;ค่าส่ง</b></h2>
                  </ion-label>
                </ion-text>
              </ion-col>
            </ion-row>
          </ion-grid>
          <ion-grid style="padding: 0px 10px 0px 10px;">
            <ion-row>
              <ion-col class="ion-padding ">
                <ion-text>
                  <ion-label>
                    <h5>Delivery</h5>
                  </ion-label>
                </ion-text>
              </ion-col>
              <ion-col class="ion-padding ion-text-right">
                <ion-text>
                  <ion-label>
                    <h2><b>ที่เหลือทั้งหมด</b></h2>
                  </ion-label>
                </ion-text>
              </ion-col>
            </ion-row>
          </ion-grid>
        </ion-card>
      </ion-card>

      <ion-card class="ion-padding-top">
        <ion-card color="tertiary" style="padding: 0px 10px 10px 10px;">
          <ion-text>
            <ion-label class="ion-padding">
              <h2 style="margin-left: 1rem;"><b>การขอข้อมูล</b></h2>
            </ion-label>
          </ion-text>
          <ion-item color="tertiary" lines="none" button routerLink="/form-input-address-by-current">
            <ion-label>
              <ion-icon name="checkmark-circle-outline" style="color: cornflowerblue"></ion-icon>
              <b>&nbsp;ที่อยู่ปัจจุบัน&nbsp;</b>
              <ion-text color="danger">*</ion-text>
              <ion-text color="medium" style="font-size: 14px">
                <ion-label class="ion-padding-top input">919/3 ม.10 บ้านศรีฐาน ต.ศิลา อ.เมือง จ.ขอนแก่น 40000
                </ion-label>
              </ion-text>
            </ion-label>
          </ion-item>
          <ion-item color="tertiary" lines="none" button routerLink="/form-input-address-by-current">
            <ion-label>
              <ion-icon name="checkmark-circle-outline" style="color: cornflowerblue"></ion-icon>
              <b>&nbsp;ข้อมูลผู้ใช้&nbsp;</b>
              <ion-text color="danger">*</ion-text>
              <ion-text color="medium" style="font-size: 14px">
                <ion-label class="ion-padding-top input">0895555555</ion-label>
              </ion-text>
            </ion-label>
          </ion-item>
          <ion-item color="tertiary" lines="none" button routerLink="/form-input-address-by-current">
            <ion-label>
              <ion-icon name="checkmark-circle-outline"></ion-icon>
              <b>&nbsp;ข้อมูลทั่วไป&nbsp;</b>
              <ion-text color="danger">*</ion-text>
              <ion-text color="medium" style="font-size: 14px">
                <ion-label class="ion-padding-top input">0895555555</ion-label>
              </ion-text>
            </ion-label>
          </ion-item>
          <ion-label style="color: cornflowerblue">
            <h6 class="ion-margin-top ion-text-center">ข้อมูลสมบูรณ์ไปแล้ว (2/3)</h6>
          </ion-label>
        </ion-card>
      </ion-card>

      <ion-card class="ion-padding-top">
        <ion-card color="tertiary" style="padding: 0px 10px 0px 10px;">
          <ion-text>
            <ion-label style="padding: 0px 10px 0px 10px;">
              <h2 style="margin-left: 1rem;"><b>ขออนุญาตให้เข้าถึงข้อมูลส่วนตัว</b></h2>
            </ion-label>
          </ion-text>
          <ion-item color="tertiary" lines="none" style="font-size: 14px">
            <ion-checkbox style="--size:1rem" mode="ios" color="warning" slot="start"></ion-checkbox>
            <ion-text>อนุญาตให้เข้าถึงข้อมูลที่จำเป็นสำหรับการให้บริการแก่คุณ</ion-text>
          </ion-item>
          <br>
        </ion-card>
      </ion-card>

      <ion-card-content>
        <ion-card>
          <div class="ion-no-margin">
            <ion-card color="tertiary" class="ion-no-padding border-radius">
              <ion-list class="ion-margin-bottom" lines="none">
                <ion-list-header mode="md" color="tertiary">
                  <ion-label>
                    <h3>ยอมรับข้อตกลง</h3>
                  </ion-label>
                </ion-list-header>
                <ion-radio-group mode="md">
                  <ion-item color="tertiary">
                    <ion-label>
                      <h3><b>อนุญาต</b></h3>
                    </ion-label>
                    <ion-radio slot="start" value="true"></ion-radio>
                  </ion-item>
                  <ion-item color="tertiary">
                    <ion-label>
                      <h3><b>ปฏิเสธ</b></h3>
                    </ion-label>
                    <ion-radio slot="start" value="false"></ion-radio>
                  </ion-item>
                </ion-radio-group>
              </ion-list>
            </ion-card>
          </div>
        </ion-card>
      </ion-card-content>

    </ion-content>
    <ion-footer class="ion-no-border">
      <ion-button color="danger" class="ion-no-margin" expand="full" type="submit">ยืนยัน</ion-button>
    </ion-footer>
  </ion-page>
</template>

<script lang="ts">
import {
  IonPage,
  IonContent,
  IonCard,
  IonCardContent,
  IonList,
  IonListHeader,
  IonItem,
  IonRadio,
  IonRadioGroup,
  IonLabel,
  IonText,
  IonHeader,
  IonToolbar,
  IonBackButton,
  IonButtons,
  IonIcon,
} from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonPage,
    IonContent,
    IonCard,
    IonCardContent,
    IonList,
    IonListHeader,
    IonItem,
    IonRadio,
    IonRadioGroup,
    IonLabel,
    IonText,
    IonHeader,
    IonToolbar,
    IonBackButton,
    IonButtons,
    IonIcon,
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
