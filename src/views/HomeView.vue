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
        <div class="education-first">
          <img src="/icons/education_icon.png" alt="education_icon" class="ed_icon" />
          <h3>Education</h3>
          <p>IT-högskolan</p>
          <p>Järfälla gymnasium</p>
        </div>

        <div class="education-second">
          <img src="/icons/education_icon.png" alt="education_icon" class="ed_icon" />
          <h3>Program</h3>
          <p>Frontend Developer</p>
          <p>Arts program</p>
        </div>

        <p>
          A patient, adaptable, and creative frontend development student with experience in
          building responsive web applications. Proficient in HTML, CSS, JavaScript, and modern
          frameworks. Passionate about delivering user-friendly solutions and high-quality user
          experiences. Enjoys teamwork and collaboration and is always eager to learn and grow.
        </p>
      </div>
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

/* fonts */
.home-first h2 {
  margin-left: 175px;
}

.home-second h2 {
  margin-top: -15px;
  margin-left: 195px;
}

.home-second p {
  margin-left: 180px;
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

/* Button */
.resume-button {
  margin-top: 25px;
  margin-left: 275px;
  border-radius: 37px;
  padding: 8px 40px;
  font-size: 18px;
  background-color: #d8d8d8;
  font-family: 'Outfit', sans-serif;
}

/* All pictures */
.profile_img {
  display: block;
  margin-left: auto;
  margin-right: 150px;
  margin-top: -485px;
  max-width: 500px;
}

.about_me_img {
  max-width: 350px;
  padding-left: 150px;
}
</style>
