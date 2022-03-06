<template>
  <div>
    <div class="container">
      <div class="row">
        <div v-for="(project, index) in getProject" :key="index" class="col-lg-4">
          <div class="card">
            <img
              v-bind:src= "project.image"
              class="card-img-top cover"
              alt="Waterfall"
            />
            <div class="card-body">
              <h5 class="card-title">{{ project.name }}</h5>
              <a :href="('project/' + project.id)" class="btn btn-priv">Detail</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import json from "../assets/data.json"
export default {
  data() {
    return{
      getProject: json,
    }
  },
}
</script>

<style scoped>
  .cover {
    object-fit: cover;
    height: 50vh;
  }
</style>
