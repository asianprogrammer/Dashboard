<script setup>
import LArrowIcon from "./icons/LArrowIcon.vue";
import RArrowIcon from "./icons/RArrowIcon.vue";
// .p85 and .p37 is course static progress width
// make it change when it need dynamic pass dynamic value and style binding
</script>
<template>
  <section class="NativeBox">
    <div class="header flex flex-y-center flex-x-between">
      <header>
        <h4>Continue courses</h4>
      </header>

      <section class="flex flex-center">
        <div class="sb NativeRound flex flex-center cursor-point">
          <div class="icon flex flex-center">
            <LArrowIcon />
          </div>
        </div>
        <div class="sb NativeRound flex flex-center cursor-point">
          <div class="icon flex flex-center">
            <RArrowIcon />
          </div>
        </div>
      </section>
    </div>

    <section class="flex courses-boxes">
      <div class="NativeCard">
        <div class="cover flex flex-center">
          <img
            width="100"
            height="100"
            class="no-select no-drag"
            src="../../public/images/DS1.jpg"
            alt="Courses"
          />
        </div>

        <div class="flex flex-y-center flex-x-between">
          <section>
            <h5>Data Science</h5>
            <span class="T-gray">Sofian Siddique</span>
          </section>
          <div class="profile">
            <img
              class="no-drag no-select"
              src="../../public/images/PRO3.jpg"
              alt="Tutor"
            />
          </div>
        </div>

        <div class="bar flex flex-center">
          <div class="progress p85"></div>
          <div class="main"></div>
        </div>

        <div class="flex sbt flex-y-center flex-x-between">
          <span class="T-gray">Completed: 85%</span>
          <span class="T-gray">Days: 15/24</span>
        </div>
      </div>
      <div class="NativeCard">
        <div class="cover flex flex-center">
          <img
            width="100"
            height="100"
            class="no-select no-drag"
            src="../../public/images/AI1.jpg"
            alt="Courses"
          />
        </div>

        <div class="flex flex-y-center flex-x-between">
          <section>
            <h5>Messing Learning</h5>
            <span class="T-gray">Usman Fayad</span>
          </section>
          <div class="profile">
            <img
              class="no-drag no-select"
              src="../../public/images/PRO9.jpg"
              alt="Tutor"
            />
          </div>
        </div>

        <div class="bar flex flex-center">
          <div class="progress p35"></div>
          <div class="main"></div>
        </div>

        <div class="flex sbt flex-y-center flex-x-between">
          <span class="T-gray">Completed: 85%</span>
          <span class="T-gray">Days: 15/24</span>
        </div>
      </div>
    </section>
  </section>
</template>
<style scoped>
.p85 {
  width: 85% !important;
}
.p35 {
  width: 35% !important;
}
.profile {
  width: 35px;
  height: 35px;
}
.courses-boxes .NativeCard {
  width: 260px;
  margin-top: 20px;
  margin-right: 20px;
}
.bar {
  margin-top: 20px;
}
.sb {
  margin: 0 5px;
}
.sbt {
  margin: 5px 0;
}
.progress {
  width: 80%;
  height: 3px;
  z-index: 99;
  position: relative;
  background: #fff;
  border-radius: 25px;
}
.main {
  width: 100%;
  height: 3px;
  background: #5a6077;
}
</style>
