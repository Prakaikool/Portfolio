<script setup></script>

<template>
  <div class="home-container">
    <div class="home-first">
      <h1>PRAKAIKOOL<br />TEEPRAKEN</h1>
      <h2>Frontend developer student</h2>

      <button @click="downLoadFile" class="resume-button">
        <img
          src="/icons/file_down_icon.png"
          alt="Download"
          style="height: 18px; margin-right: 5px"
        />Resume
      </button>

      <img src="/images/profile_img.png" alt="Profile image" class="profile_img" />
    </div>

    <div class="home-second">
      <p>Get to know more</p>
      <h2>About me</h2>

      <img src="/images/about_me_img.png" alt="My image" class="about_me_img" />

      <div class="education-container">
        <div class="education-box">
          <div class="education-first">
            <img src="/icons/education_icon.png" alt="education_icon" class="ed_icon" />
            <h3>2024-2026</h3>
            <p>Frontend Developer</p>
            <p>IT-högskolan</p>
          </div>

          <div class="education-second">
            <img src="/icons/education_icon.png" alt="education_icon" class="ed_icon" />
            <h3>2018-2021</h3>
            <p>Arts program</p>
            <p>Järfälla gymnasium</p>
          </div>
        </div>

        <div class="education-p">
          <p>
            A patient, adaptable, and creative frontend development student with experience in
            building responsive web applications. Proficient in HTML, CSS, JavaScript, and modern
            frameworks. Passionate about delivering user-friendly solutions and high-quality user
            experiences. Enjoys teamwork and collaboration and is always eager to learn and grow.
          </p>
        </div>
      </div>
    </div>

    <div class="project-container">
      <h3>Latest projects</h3>

      <div class="project-box">
        <div class="project-first">
          <img src="" alt="" />
          <h3>Projects name</h3>
        </div>
        <div class="project-second">
          <img src="" alt="" />
          <h3>Projects name</h3>
        </div>
      </div>
      <h3>More</h3>
    </div>

    <div>
      <h3>Frontend development</h3>
      <p>Skills and tools</p>
      <ul class="skills-1">
        <li>HTML</li>
        <li>CSS</li>
        <li>Java Script</li>
        <li></li>
      </ul>
      <ul class="skills-2">
        <li>React</li>
        <li>UX&UI</li>
        <li></li>
        <li>Typescript</li>
      </ul>
      <ul class="skills-3">
        <li>React</li>
        <li>SQL</li>
        <li></li>
        <li>Full-stack</li>
      </ul>
      <ul class="skills-4">
        <li>Agil</li>
        <li>Vue</li>
        <li></li>
        <li>Graphic framework</li>
      </ul>
    </div>

    <div>
      <h3>Hobby</h3>
    </div>
  </div>
</template>

<style scoped>
/* Base */
.home-container {
  color: black;
  max-width: 100%;
  padding: 100px;
}

/* Sections */
.home-first {
  margin-top: 100px;
}

.home-second {
  margin-top: 100px;
}

.education-first {
  max-width: 300px;
  padding: 20px;
  border: 2px solid #000;
  border-radius: 37px;
  text-align: center;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.education-second {
  max-width: 300px;
  padding: 20px;
  border: 2px solid #000;
  border-radius: 37px;
  text-align: center;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
  margin-top: -176px;
  margin-left: 345px;
}

.education-box {
  margin-top: -378px;
  margin-left: 480px;
}

.project-container {
  margin-top: 100px;
}

.project-box {
  max-width: 200px;
  padding: 20px;
  border: 2px solid #000;
  border-radius: 37px;
  margin-left: 170px;
  text-align: center;
}

/* fonts */
.home-first h2 {
  margin-left: 175px;
}

.home-second h2 {
  margin-top: -15px;
  margin-left: 215px;
}

.home-second p {
  margin-left: 200px;
}

h1 {
  font-size: 56px;
  color: #004aad;
  font-family: 'Archivo Black', sans-serif;
  padding-left: 150px;
}

h2 {
  font-size: 22px;
  font-family: 'Archivo Black', sans-serif;
}

p {
  font-size: 18px;
  font-family: 'Outfit', sans-serif;
}

.education-container h3 {
  margin-top: 0;
  margin-bottom: 8px;
}

.education-p {
  padding-right: 170px;
  margin-left: 280px;
  margin-top: 50px;
}

.education-first p {
  margin-top: 0;
  margin-bottom: 4px;
  margin-left: auto;
}

.education-second p {
  margin-top: 0;
  margin-bottom: 4px;
  margin-left: auto;
}

/* Button */
.resume-button {
  margin-top: 25px;
  margin-left: 275px;
  border-radius: 37px;
  padding: 8px 40px;
  font-size: 18px;
  background-color: #d8d8d8;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
  font-family: 'Outfit', sans-serif;
}

/* All pictures and icons */
.profile_img {
  display: block;
  margin-left: auto;
  margin-right: 150px;
  margin-top: -485px;
  max-width: 500px;
}

.about_me_img {
  max-width: 400px;
  padding-left: 150px;
}

.ed_icon {
  width: 40px;
  height: auto;
  margin-bottom: 10px;
}
</style>
