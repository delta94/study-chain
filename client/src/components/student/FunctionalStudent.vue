<template>
  <ul class="nav flex-column">
    <li class="nav-item">
      <router-link class="nav-link color-black" to="/student">
        <i class="color-999 fas fa-home"></i>
        Dashboard
      </router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link color-black" :to="`/student/mysubjects`">
        <i class="color-999 fas fa-layer-group"></i>
        My Subjects
      </router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link color-black" :to="`/student/mycertificates`">
        <i class="color-999 fas fa-award"></i>
        My Certificates
      </router-link>
    </li>
  </ul>
</template>

<script>
export default {
  name: "functionalStudent"
};
</script>
