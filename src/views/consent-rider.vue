<template>
    <ion-page>

        <ion-header>
            <ion-toolbar color="tertiary" mode="ios">
                <ion-buttons slot="start">
                    <ion-back-button color="primary" style="font-weight: 900; margin-left: 1rem;" icon="arrow-back"
                        default-href="" text="&nbsp;&nbsp;คำขออนุญาตให้คุณเป็น Rider">
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
                    <ion-grid class="ion-no-padding ion-padding-top ion-padding-bottom ion-padding-right">
                        <ion-row>
                            <ion-col class="ion-no-padding">
                                <ion-text>
                                    <ion-label>
                                        <h2><b>คำขอดำเนินการสมัครสมาชิก</b></h2>
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
                            เทศบาลเมืองชะอำต้องการเชื่อมต่อกับ<b>&nbsp;อานนท์
                                บางสาน</b>&nbsp;ของคุณเพื่อความสะดวกในการชำระค่าบริการโปรดอ่าน และยินยอม
                            ข้อตกลง
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
                <ion-card color="tertiary" style="padding:10px 0px 0px 10px;">
                    <ion-text>
                        <ion-label class="ion-no-padding">
                            <h2 ><b>โปรดยืนยัน</b></h2>
                        </ion-label>
                    </ion-text>
                    <ion-item color="tertiary" lines="none" style="font-size: 14px" class="ion-no-padding">
                        <ion-checkbox style="--size:1rem" mode="ios" color="warning" slot="start"></ion-checkbox>
                        <ion-text>ฉันอ่านและยอมรับข้อตกลงแล้ว</ion-text>
                    </ion-item>
                    <br>
                </ion-card>
            </ion-card>

            <ion-card class="ion-padding-top">
                <ion-card color="tertiary" style="padding:10px 0px 0px 10px;">
                    <ion-text>
                        <ion-label class="ion-no-padding">
                            <h2 ><b>โปรดระบุตัวเลือก</b></h2>
                        </ion-label>
                    </ion-text>
                    <ion-item color="tertiary" lines="none" style="font-size: 14px" class="ion-no-padding">
                        <ion-checkbox style="--size:1rem" mode="ios" color="warning" slot="start"></ion-checkbox>
                        <ion-text>แจ้งเตือนค่าขยะรายเดือนที่หน้า Home ของ mana</ion-text>
                    </ion-item>
                    <ion-item color="tertiary" lines="none" style="font-size: 14px" class="ion-no-padding">
                        <ion-checkbox style="--size:1rem" mode="ios" color="warning" slot="start"></ion-checkbox>
                        <ion-text>แจ้งเตือนค่าขยะรายเดือนที่หน้า Home ของ mana</ion-text>
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
} from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'ConsentRider',
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
