<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        <span class="firstname">anna</span> <span class="middlename">hope</span>
         <span class="lastname"> melnikov</span>
      </h1>
      <div class="links">
        <NuxtLink to="/cv" class="button--grey">cv</NuxtLink>
        <a
          href="https://github.com/notnami"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          github
        </a>
        <a
          href="https://www.linkedin.com/in/anna-melnikov/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          linkedin
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #e2e0e8;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 2px;
}

.firstname {
  color: #55cdfc;
}

.middlename {
  color: #fffdfb;
}

.lastname {
  color: #f798b3;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
  
}

</style>
