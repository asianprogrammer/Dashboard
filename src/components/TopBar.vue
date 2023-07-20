<script setup>
import ProjectIcon from "./icons/ProjectIcon.vue";
import NoteIcon from "./icons/NoteIcon.vue";
import CalenderIcon from "./icons/CalenderIcon.vue";
import DownArrowIcon from "./icons/DownArrowIcon.vue";
import SearchIcon from "./icons/SearchIcon.vue";
import SunIcon from "./icons/SunIcon.vue";
import MoonIcon from "./icons/MoonIcon.vue";
import BallICon from "./icons/BallIcon.vue";
import SettingIcon from "./icons/SettingIcon.vue";
import DownIcon from "./icons/DownIcon.vue";
</script>
<template>
  <section class="NaveBar flex flex-y-center flex-x-between">
    <div class="NativeBtn flex flex-center">
      <div class="icon flex flex-center">
        <ProjectIcon />
      </div>
      <span class="T-gray">Project</span>
    </div>
    <div class="NativeBtn flex flex-center">
      <div class="icon flex flex-center">
        <NoteIcon />
      </div>
      <span class="T-gray">Planning</span>
    </div>
    <div class="NativeBtn flex flex-y-center flex-x-even">
      <div class="icon flex flex-center">
        <CalenderIcon />
      </div>
      <span class="T-gray">Calendar</span>
      <div class="icon flex flex-center">
        <DownArrowIcon />
      </div>
    </div>
    <div class="NativeBtn flex flex-between">
      <div class="icon flex flex-center">
        <SearchIcon />
      </div>
      <input type="search" placeholder="Search or type command" />
    </div>
    <div class="NativeBtn fixed-Height flex flex-center">
      <div class="icon dative flex flex-center">
        <SunIcon />
      </div>
      <div class="icon active flex flex-center">
        <MoonIcon />
      </div>
    </div>
    <div class="NativeBtn flex flex-center">
      <div class="icon flex flex-center">
        <BallICon />
      </div>
    </div>
    <div class="NativeBtn flex flex-center">
      <div class="icon flex flex-center">
        <SettingIcon/>
      </div>
    </div>
    <div class="NativeBtn flex flex-center">
        <div class="icon flex flex-center">
            <DownIcon />
        </div>
        <span class="T-gray">Export Data</span>
        <div class="text T-gray active">.json</div>
    </div>
    <div class="NativeBtn flex flex-y-center flex-x-between">
        <div class="profile">
            <img src="../../public/images/PRO4.jpg" alt="Profile Image">
        </div>
        <span class="T-gray">&nbsp; Mohammad Ali&nbsp;</span>
        <div class="icon flex flex-center">
            <DownArrowIcon />
        </div>
    </div>
  </section>
</template>
<style scoped>
.profile {
    width: 30px;
    height: 30px;
}
.text.active {
    padding: 5px 10px;
    margin-left: 5px;
    border-radius: 7px;
    background: #252A41;
}
.NativeBtn span {
  margin-left: 5px;
}
.fixed-Height {
  width: 130px;
  height: 40px;
  padding: 0;
}
.icon.dative {
  width: 60px;
  height: 10px;
  padding: 14px;
}
.icon.active {
  width: 60px;
  height: 35px;
  padding: 0 20px;
  border-radius: 12px;
  background: #010516;
}
.NaveBar {
  margin-top: 20px;
}
input {
  width: 450px;
  margin-left: 5px;
}
input::placeholder {
  color: var(--gray);
}
</style>
