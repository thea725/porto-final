<template>
  <div class="container">

    <div v-for="(project, index) in getProject" :key="index">
      <div v-if="project.id == $route.params.id">
        <div class="d-flex align-items-center">
          <div class="flex-shrink-0" style="margin-right: 2rem">
            <img :src="project.image" :alt="project.name">
          </div>
          <div class="flex-grow-1 ms-3">
                <h5 class="card-title left">{{ project.name }}</h5>
                <p class="card-text left">{{ project.description }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import json from "../assets/data.json";

export default{
  data() {
    return {
      getProject: json,
    }
  },
}
</script>