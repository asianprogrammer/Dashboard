<script setup>
import CalenderIcon from "./icons/CalenderIcon.vue";
import ClockIcon from "./icons/ClockIcon.vue";
import NaveIcon from "./icons/NaveIcon.vue";
import TrashIcon from "./icons/TrashIcon.vue";
import InboxIcon from "./icons/InboxIcon.vue";
</script>
<template>
  <section class="NativeBox">
    <div class="header">
      <header class="flex flex-y-center flex-x-between">
        <h4>Notifications</h4>
        <div class="flex flex-y-center clearBtn">
          <div class="icon flex flex-center">
            <TrashIcon />
          </div>
          <spn class="T-gray">Clear</spn>
        </div>
      </header>
    </div>

    <section class="flex flex-y-down courses-boxes">
      <div class="flex flex-y-center flex-x-between">
        <h5>Upcoming event</h5>
        <div class="icon flex flex-center">
          <NaveIcon />
        </div>
      </div>
      
      <span class="T-gray">Product design meeting | Time: 4h 5m</span>
     
      <div class="MT date-time flex flex-y-center">
        <div class="icon flex flex-center">
          <CalenderIcon />
        </div>
        <span class="T-gray">Wed 20 Apr</span>
      </div>
      <div class="date-time flex flex-y-center">
        <div class="icon flex-center">
          <ClockIcon />
        </div>
        <span class="T-gray">10 Am - 12:5 AM</span>
      </div>
    </section>

    <section class="flex flex-y-down courses-boxes">
      <div class="flex flex-y-center flex-x-between">
        <h5>Message - Product design</h5>
        <div class="icon flex flex-center">
          <NaveIcon />
        </div>
      </div>
      
      <div class="date-time flex flex-y-center">
        <div class="icon flex flex-center">
          <InboxIcon />
        </div>
        <span class="T-gray">Message from Haroon Imam</span>
      </div>
      
      <div class="mgs MT">
        Hey team. just wanted to check in and see how is..
      </div>
    </section>

  </section>
</template>
<style scoped>
.mgs {
  color: #656682;
  padding: 10px 10px;
  background: #1D1E35;
  border-radius: 12px;
}
.date-time {
  margin: -3px 0;
}
.date-time .icon {
  margin-right: 5px;
}
.courses-boxes {
  width: 500px;
  padding: 14px 20px;
  margin-top: 15px;
  border-radius: 12px;
  background: #252a41;
}
.MT {
  margin-top: 20px;
}
</style>
