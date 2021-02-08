<template>

<div class="resume">
<h1>anna melnikov</h1>
<span class="c4 c1">Machine Learning engineer with a
focus on NLP and big data. Experienced with leading projects,
organizing work across remote and distributed teams with diverse
areas of expertise. Focused on delivering high-value products with
clear metrics to reach concrete business goals for organizations
and their clients.</span>

<p class="c9"></p>
<p class="c7"><span class="highlights">Highlights</span></p>

<ul>
  <li>Over 5 years of professional experience with Python</li>
  <li>Machine Learning
    <ul>
      <li>Pytorch, Tensorflow, sklearn</li>
    </ul></li>
  <li>Data processing and analysis: PySpark, Pandas, Dask</li>
  <li> Cloud
    <ul>
      <li>AWS: S3, EMR, Lambda, Athena, Sagemaker, CloudWatch</li>
      <li>Google Cloud Platform: Kubernetes Engine, Container Registry, Google Storage, Firestore, Stackdriver</li>
    </ul>  
  </li>  
  <li>Containers: Docker, Kubernetes</li>
  <li>Data: MongoDB, Athena (PrestoDB), Hive, PostgreSQL</li>
  <li>Web: Flask, async HTTP</li>
</ul>

      <div class="links">
        <a href="/resume_anna.pdf"
           target="_blank"
         class="button--grey">full cv</a>
        <a 
           href="/"
           class="button--blue">home</a>
      </div>
</div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>

.resume {
  margin: 0 auto;
  min-height: 100vh;
  justify-content: center; 
  align-items: center;
  text-align: left;
  color: #000;
  font-size: 20px;
  margin-top: 15px;
  margin-left: 20px;
}


.highlights {
  font-style: bold;
  color: #FF33B1;
  font-size: 24px;
}
</style>

