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
      <header class="flex flex-y-center flex-x-between">
        <h4>Calender</h4>

        <div class="ActiveBtn flex flex-y-center clearBtn">
          <div class="icon flex flex-center">
            <DateIcon />
          </div>
          <spn class="T-gray">Years</spn>
          <div class="icon flex flex-center">
            <DownIcon />
          </div>
        </div>
      </header>
    </div>

    <section class="flex flex-y-down courses-boxes">
        <Calendar :attributes="attrs" title-position="left" trim-weeks is-dark="true" expanded />
    </section>

    <section class="flex flex-y-center mgs">
      <div class="icon flex flex-center">
        <ReadyIcon />
      </div>
      Finish the report for the client meeting
    </section>

    <section class="flex flex-y-down mgs disable">
      <div class="flex flex-y-center">
        <div class="icon flex flex-center">
        <ReadyIcon />
      </div>
      <span>Review the budget for the upcoming quarter</span>
      </div>
      <span class="T-gray ML-30px">Analyze the revenue for the last 3 months</span>
    </section>


  </section>
</template>
<style scoped>
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
