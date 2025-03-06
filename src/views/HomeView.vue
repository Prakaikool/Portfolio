<script setup></script>

<template>
  <div class="home-container">
    <div class="home-first">
      <h1>PRAKAIKOOL<br />TEEPRAKEN</h1>
      <h2>Frontend developer student</h2>

      <button @click="downLoadFile" class="resume-button">Resume</button>

      <img src="/images/profile_picture.png" alt="Profile picture" class="picture" />
    </div>

    <p>Get to know more</p>
    <h2>About me</h2>

    <img src="" alt="" />

    <div class="education-program-box">
      <div class="education">
        <h3>Education</h3>
        <p>IT-högskolan</p>
        <p>Järfälla gymnasium</p>
      </div>

      <div class="program">
        <h3>Program</h3>
        <p>Frontend Developer</p>
        <p>Arts program</p>
      </div>

      <p>
        A patient, adaptable, and creative frontend development student with experience in building
        responsive web applications. Proficient in HTML, CSS, JavaScript, and modern frameworks.
        Passionate about delivering user-friendly solutions and high-quality user experiences.
        Enjoys teamwork and collaboration and is always eager to learn and grow.
      </p>
    </div>

    <div>
      <h3>Latest projects</h3>
      <img src="" alt="" />
      <h3>Projects name</h3>

      <img src="" alt="" />
      <h3>Projects name</h3>

      <h3>More</h3>
    </div>

    <div>
      <h3>Frontend development</h3>
      <p>Skills and tools</p>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Java Script</li>
      </ul>
    </div>

    <div>
      <h3>Hobby</h3>
    </div>
  </div>
</template>

<style scoped>
.home-container {
  color: black;
  max-width: auto;
  padding: 100px 150px;
}

.home-first {
  margin-top: 100px;
}

.home-first h2 {
  margin-left: 125px;
}

.resume-button {
  margin-top: 25px;
  margin-left: 215px;
  border-radius: 37px;
  padding: 8px 40px;
  font-size: 18px;
  background-color: #d8d8d8;
  font-family: 'Outfit', sans-serif;
}

h1 {
  font-size: 56px;
  color: #004aad;
  font-family: 'Archivo Black', sans-serif;
  padding-left: 100px;
}

h2 {
  font-size: 22px;
  font-family: 'Archivo Black', sans-serif;
}

p {
  font-size: 18px;
  font-family: 'Outfit', sans-serif;
}

.picture {
  display: block;
  margin-left: auto;
  margin-right: 0;
  margin-top: -485px;
  max-width: 500px;
}
</style>
