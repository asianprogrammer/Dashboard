<script setup>
import AddIcon from "./icons/AddIcon.vue";
import NavIcon from "./icons/NaveIcon.vue";
import LinkIcon from "./icons/LinkIcon.vue";
import EditIcon from "./icons/EditIcon.vue";
import ShareIcon from "./icons/ShareIcon.vue";
import LayoutAltIcon from "./icons/LayoutAltIcon.vue";
import GridIcon from "./icons/GridIcon.vue";
import LayoutIcon from "./icons/LayoutIcon.vue";
import FilterIcon from "./icons/FilterIcon.vue";
import DownIcon from "./icons/DownArrowIcon.vue";
// .p85 and .p37 is course static progress width
// make it change when it need dynamic pass dynamic value and style binding
</script>
<template>
  <section class="NativeBox">
    <div class="header flex flex-y-center flex-x-between">
      <header class="flex flex-y-center">
        <div>
          <h4>Continue courses</h4>
        </div>
        <div class="users ML-40px flex flex-y-center">
          <div class="profile">
            <img src="../../public/images/PRO.jpg" alt="Client Image" />
          </div>
          <div class="profile">
            <img src="../../public/images/PRO8.jpg" alt="Client Image" />
          </div>
          <div class="profile">
            <img src="../../public/images/PRO11.jpg" alt="Client Image" />
          </div>
          <div class="profile">
            <img src="../../public/images/PRO12.jpg" alt="Client Image" />
          </div>

          <div class="profile">
            <img src="../../public/images/PRO2.jpg" alt="Client Image" />
          </div>
          <div class="add flex flex-center">
            <AddIcon />
          </div>
        </div>
      </header>

      <div class="interactive flex flex-y-center flex-x-between">
        <div class="flex flex-y-center flex-x-even MW">
          <div class="icon flex flex-center">
            <EditIcon />
          </div>
          <span>Edit</span>
        </div>

        <div class="flex flex-y-center flex-x-even MW">
          <div class="icon flex flex-center">
            <ShareIcon />
          </div>
          <span>Share</span>
        </div>

        <div class="ActiveBtn flex flex-y-center flex-x-between">
          <div class="icon flex flex-center">
            <FilterIcon />
          </div>
          <span class="T-gray">Filter</span>
          <div class="icon flex flex-center">
            <DownIcon />
          </div>
        </div>

        <div class="ActiveBtn flex fle-y-center flex-x-between">
          <div class="icon flex flex-center">
            <LayoutAltIcon />
          </div>
          <div class="icon active flex flex-center">
            <GridIcon />
          </div>
          <div class="icon flex flex-center">
            <LayoutIcon />
          </div>
        </div>

      </div>
    </div>

    <section class="flex courses-boxes">
      <div class="NativeCard">
        <div class="header flex flex-x-between">
          <h5>Create a logo for a new company</h5>
          <div class="icon flex flex-center">
            <NavIcon />
          </div>
        </div>

        <div class="tag active sbt flex flex-y-center">
          <div class="icon bg flex flex-center">
            <AddIcon />
          </div>
          <span>Tag</span>
        </div>

        <p class="T-gray sbt">
          Create effective logo that accurately represents the mission of the
          company
        </p>

        <div class="flex flx-y-center flex-x-between MT">
          <div class="users flex flex-y-center">
            <div class="profile">
              <img src="../../public/images/PRO10.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO8.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO9.jpg" alt="Client Image" />
            </div>
            <div class="add flex flex-center">
              <AddIcon />
            </div>
          </div>
          <div class="flex flex-center">
            <div class="icon flex flex-center">
              <LinkIcon />
            </div>
            <span>23 Files</span>
          </div>
        </div>

        <div class="bottom-progress flex flex-y-center flex-x-between">
          <div>85%</div>
          <div class="progress-container">
            <div class="progress p1"></div>
            <div class="main"></div>
          </div>
          <div>18<span class="T-gray">/32</span></div>
        </div>
      </div>

      <div class="NativeCard">
        <div class="header flex flex-x-between">
          <h5>Design a website landing page</h5>
          <div class="icon flex flex-center">
            <NavIcon />
          </div>
        </div>

        <div class="flex sbt flex-y-center W1">
          <div class="tag flex flex-center">
            <span>UI design</span>
          </div>
          <div class="tag flex flex-center">
            <span>Landing</span>
          </div>
          <div class="tag active flex flex-y-center">
            <div class="icon bg flex flex-center">
              <AddIcon />
            </div>
            <span>Tag</span>
          </div>
        </div>

        <p class="T-gray sbt">
          An attractive and user-friendly landing page for a website
        </p>

        <div class="flex flx-y-center flex-x-between MT">
          <div class="users flex flex-y-center">
            <div class="profile">
              <img src="../../public/images/PRO2.jpg" alt="Client Image" />
            </div>
            <div class="add flex flex-center">
              <AddIcon />
            </div>
          </div>
          <div class="flex flex-center">
            <div class="icon flex flex-center">
              <LinkIcon />
            </div>
            <span>3 Files</span>
          </div>
        </div>

        <div class="bottom-progress flex flex-y-center flex-x-between">
          <div>15%</div>
          <div class="progress-container">
            <div class="progress p2"></div>
            <div class="main"></div>
          </div>
          <div>2<span class="T-gray">/34</span></div>
        </div>
      </div>

      <div class="NativeCard">
        <div class="header flex flex-x-between">
          <h5>Create a logo for a new company</h5>
          <div class="icon flex flex-center">
            <NavIcon />
          </div>
        </div>

        <div class="flex W1 sbt">
          <div class="tag flex flex-y-center">
            <span>Packaging</span>
          </div>
          <div class="tag active flex flex-y-center">
            <div class="icon bg flex flex-center">
              <AddIcon />
            </div>
            <span>Tag</span>
          </div>
        </div>

        <p class="T-gray sbt">
          Create effective logo that accurately represents the mission of the
          company
        </p>

        <div class="flex flx-y-center flex-x-between MT">
          <div class="users flex flex-y-center">
            <div class="profile">
              <img src="../../public/images/PRO.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO8.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO11.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO12.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO3.jpg" alt="Client Image" />
            </div>
            <div class="profile">
              <img src="../../public/images/PRO2.jpg" alt="Client Image" />
            </div>
            <div class="add flex flex-center">
              <AddIcon />
            </div>
          </div>
          <div class="flex flex-center">
            <div class="icon flex flex-center">
              <LinkIcon />
            </div>
            <span>7 Files</span>
          </div>
        </div>

        <div class="bottom-progress flex flex-y-center flex-x-between">
          <div>50%</div>
          <div class="progress-container">
            <div class="progress" style="width: 50% !important"></div>
            <div class="main"></div>
          </div>
          <div>17<span class="T-gray">/34</span></div>
        </div>
      </div>
    </section>
  </section>
</template>
<style scoped>
.MW {
  margin: 0 10px;
}
.icon.active {
  width: 35px;
  height: 35px;
  padding: 10px;
  margin-top: -2.5px; 
  border-radius: 50%;
  background: #A948F2;
}
.W1 {
  width: 100%;
}
.bottom-progress {
  margin-top: 27px;
}
.progress-container {
  width: 70%;
  height: 3px;
}
.users div {
  width: 30px;
  height: 30px;
  margin-left: -10px;
  border: solid 2px #252a43;
}
.add {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  backdrop-filter: blur(10px);
  background: rgba(255, 255, 255, 0.2);
}
.add svg {
  stroke: #fff;
}
.bg {
  width: 19px;
  height: 19px;
  padding: 5px;
  margin-left: -9px;
  border-radius: 50%;
  background: #d3d7ea;
}
.tag {
  height: 26px;
  padding: 10px 10px;
  width: fit-content;
  text-align: center;
  border-radius: 20px;
  background: #141625;
  margin-right: 5px !important;
  justify-content: flex-start;
}
.tag.active {
  width: 65px;
  padding: 1px 15px;
  background: #60627f;
}
.NativeBox {
  width: 92% !important;
}
.profile {
  width: 35px;
  height: 35px;
}
.courses-boxes .NativeCard {
  width: 350px;
  margin: 0 10px;
  margin-top: 50px;
}
.sbt {
  margin: 15px 0;
}
.progress-container {
  position: relative;
}
.progress {
  width: 85%;
  height: 3px;
  z-index: 99;
  position: absolute;
  background: #fff;
  border-radius: 25px;
}
.main {
  width: 100%;
  height: 3px;
  background: #5a6077;
}
.p1 {
  width: 85%;
}
.p2 {
  width: 15%;
}
.MT {
  margin-top: 30px;
}
</style>
