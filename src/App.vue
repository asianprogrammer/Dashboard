<script setup>
import NaveUI from "./components/NaveUI.vue";
import TopBar from "./components/TopBar.vue";
import CoursesUI from "./components/CoursesUI.vue";
import NotifyUI from "./components/NotifyUI.vue";
</script>
<template>
  <section>
    <div>
      <NaveUI />
    </div>
    <div class="HW">
      <div>
        <TopBar />
      </div>
      <div class="flex Left">
        <div class="wget">
          <CoursesUI />
        </div>
        <div class="wget">
          <NotifyUI />
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
.HW {
  width: 91%;
  margin-left: 7%;
}
.wget {
  margin-top: 15px;
  margin-right: 15px;
}
.MT {
  width: fit-content;
  margin-top: 20px;
}
.Left {
  width: 63%;
  flex-wrap: wrap;
}
</style>
