<template>
  <div>
    <b-jumbotron>
      <template #header>Welcome</template>

      <b-container>
        <p class="lead">
          Welcome to my portfolio website created using Vue JS, this portfolio
          website contains a contact page and some of the work I have created.
          The entire website was published on GitHub.
        </p>

        <hr class="my-4" />
        <div class="d-flex align-items-center">
          <div class="flex-shrink-0" style="margin-right: 2rem">
            <img src="../assets/foto.jpg" style="max-width: 10vw" />
          </div>
          <div class="flex-grow-1 ms-3">
            <h5 class="card-title left">About Me</h5>
            <p class="card-text left">
              My name is Muhammad Rifki Muchtar, I am a student majoring in
              instrumentation at Brawijaya University, I like to learn new
              things outside of my studies. I have the skills to build websites,
              do c programming, design circuits, and use design software like
              Adobe Photoshop and Illustrator. Some of the projects I've worked
              on were UI/UX design, implementation of object detection using AI,
              and IoT network systems.
            </p>
          </div>
        </div>
      </b-container>
    </b-jumbotron>
  </div>
</template>

<style>
.left {
  text-align: left;
}
.right {
  float: right;
}
.container {
  margin-top: 3rem;
}
</style>
