<script setup>
import { ref } from 'vue';
import { Calendar } from 'v-calendar';
import 'v-calendar/style.css';
import CalenderIcon from "./icons/CalenderIcon.vue";
import ClockIcon from "./icons/ClockIcon.vue";
import NaveIcon from "./icons/NaveIcon.vue";
import DateIcon from "./icons/CalenderIcon.vue";
import TrashIcon from "./icons/TrashIcon.vue";
import InboxIcon from "./icons/InboxIcon.vue";
import DownIcon from "./icons/DownArrowIcon.vue";
import ReadyIcon from "./icons/CheckIcon.vue";
import LoveIcon from "./icons/LoveIcon.vue";

const attrs = ref([
  {
    key: 'today',
    highlight: true,
    dates: new Date(),
  },
]);
</script>
<template>
  <section class="NativeBox">
    <div class="header">
      <header class="flex flex-y-center ">
        <h4>Team chat <span class="T-gray">•</span></h4>

        <span class="T-gray space">Activity</span>
        <span class="T-gray space">Meetings</span>
      </header>
    </div>

    <div class="hr T-gray flex flex-center">Today</div>

    <section class="flex flex-y-down mgs-box">
        <div class="msg flex">
        <div class="profile">
            <img class="image no-select no-drag" src="../../public/images/PRO6.jpg" alt="User" >
        </div>

        <div class="message flex flex-y-down">
            <span class="name">Fatima</span>
            <span class="T-gray">Hi! I am just getting organized for the week ahead</span>
        
            <div class="action flex flex-y-center flex-x-between">
                <div class="like flex flex-y-center">
                    <div class="icon flex flex-center">
                        <LoveIcon />
                    </div>
                    <span>30</span>
                </div>
                <span class="T-gray">11.30</span>
            </div>
        </div>
      </div>

      <br>
      <div class="msg flex">
        <div class="profile">
            <img class="image no-select no-drag" src="../../public/images/PRO7.jpg" alt="User" >
        </div>

        <div class="message flex flex-y-down">
            <span class="name">Fiza</span>
            
            <div class="img flex flex-center">
                <img src="../../public/images/light.jpg" alt="" srcset="">
            </div>
        
            <div class="action flex flex-y-center flex-x-between">
                <div class="like flex flex-y-center">
                    <div class="icon flex flex-center">
                        <LoveIcon />
                    </div>
                    <span>30</span>
                </div>
                <span class="T-gray">11.30</span>
            </div>
        </div>
      </div>
    </section>

  </section>
</template>
<style scoped>
.img {
    margin-top: 10px;
    overflow: hidden;
    margin-left: 5px;
    border-radius: 25px;
}
.img img {
    width: 100%;
    height: 100%;
    transform: translateY(-500px);
    object-fit: contain;
}
.message  {
    width: 455px;
    padding: 10px 20px;
    border-radius: 12px;
    background: #252A41;
}
.profile {
    width: 30px;
    height: 30px;
    margin-right: 15px;
}
.message .T-gray {
    margin: 10px 0;
}
.like {
    padding: 2px 10px;
    border-radius: 25px;
    background: #000000;
}
.space {
    margin: 0 30px;
}
.NativeBox {
  width: fit-content;
}
.courses-boxes,
.mgs {
  width: 500px;
  padding: 14px 20px;
  margin-top: 15px;
  border-radius: 12px;
  background: #252a41;
}
.mgs {
  padding: 8px 20px;
  background: #252A41;
}
.mgs.disable {
  opacity: .4;
}
</style>
