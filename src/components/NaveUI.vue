<script setup>
import PieIcon from "./icons/PieIcon.vue";
import CapIcon from "./icons/CapIcon.vue";
import NoteIcon from "./icons/NoteIcon.vue";
import BookMarkIcon from "./icons/BookMarkIcon.vue";
import CalenderIcon from "./icons/CalenderIcon.vue";
import LogoutIcon from "./icons/LogoutIcon.vue";
import InboxIcon from "./icons/InboxIcon.vue";
import DashIcon from "./icons/DashIcon.vue";
import RoundIcon from "./icons/RoundIcon.vue";
</script>
<template>
  <dev class="Nave">
    <nav class="flex flex-y-down flex-y-center">
      <div class="logo">
        <img width="100" height="100" class="no-select no-drag image" src="../../public/images/logo.png" alt="" srcset="">
      </div>

      <div class="naves">
        <div class="list active flex flex-y-center">
          <DashIcon />
        </div>
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <PieIcon />
          </div>
        </div>
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <NoteIcon />
          </div>
        </div>
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <CalenderIcon />
          </div>
        </div>
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <BookMarkIcon />
          </div>
        </div>
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <CapIcon />
          </div>
        </div>
      </div>

      <section class="bottom">
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <InboxIcon />
          </div>
        </div>
        <div class="list flex flex-y-center">
          <div class="icon flex flex-center">
            <LogoutIcon />
          </div>
        </div>
      </section>
    </nav>
    <div class="filter flex flex-center">
      <RoundIcon />
    </div>
  </dev>
</template>
<style scoped>
.logo {
  margin-top: 50px;
  margin-bottom: 70px;
}
.Nave {
  width: 80px;
  height: 95vh;
  margin-top: 30px;
  margin-left: 30px;
  border-radius: 12px;
  position: fixed;
  overflow: hidden;
}
.Nave nav {
  z-index: 99;
  height: 100%;
  backdrop-filter: blur(20px);
  background: rgba(29, 30, 53, 0.096);
}
.bottom {
  bottom: 10px;
  position: absolute;
}
.list.active {
  z-index: 9;
}
.list {
  margin: 10px 0;
}
.list.active::after {
  content: '';
  width: 8px;
  right: 9px;
  height: 8px;
  border-radius: 50%;
  position: absolute;
  background: #C653F6;
}
.filter {
  right: 0;
  top: 160px;
  width: 50px;
  height: 50px;
  position: absolute;
  z-index: -9999;
}
</style>
