<template>
  <div class="cv"> 
   <div class="intro">
    <div class="section">
      <h2>Hi there!</h2>
      <p>
        My name is Magnus Haxen, and I am a huge enthusiast of deep learning and artificial intelligence. I recently graduated from Aarhus University with a Bachelor's degree in Computer Science, where I focused on AI and deep learning as part of my studies.
        During my time at Aarhus University, I had the opportunity to learn from some of the leading experts in the field and work on various projects that allowed me to apply my knowledge in a practical setting. I also had the unique experience of completing half of my degree during the pandemic, which presented its own set of challenges but ultimately helped me to become even more resilient and adaptable.
        In my free time, you can find me staying up-to-date on the latest research and developments within the field of AI and deep learning. My ultimate career goal is to land a job at a well-respected company where I can put my skills and passion to good use and make a positive impact in the world of artificial intelligence. With my dedication, drive, and now a solid foundation in computer science and AI, I am confident that I can achieve this dream and more.
      </p>
    </div>
   </div>
   <div class="education">
    <div class="section">
      <h2>Education</h2>
      <ul>
        <li>
          Bachelor's Degree in Computer Science, Aarhus University, 2021
        </li>
      </ul>
    </div>
   </div>
   <div class="publications">
    <div class="section">
      <h2>Publications</h2>
      <ul>
        <li>
          <a href="https://dl.acm.org/doi/10.1145/3459637.3482072">
            "Center Point Query Authentication", CIKM2021 conference, 2021
          </a>
        </li>
      </ul>
    </div>
   </div>
   <div class="work_experience">
    <div class="section">
      <h2>Work Experience</h2>
      <ul>
        <li>
          Software Developer, AeroGuest ApS, 2021-2022
        </li>
      </ul>
    </div>
   </div>
   <div class="online_courses">
    <div class="section">
      <h2>Online Courses</h2>
      <p>
        Throughout my journey in the field of artificial intelligence, I have dedicated myself to continuously learning and expanding my skillset. This dedication led me to enroll in the "Machine Learning A-Z" course on Udemy, where I gained a strong foundation in machine learning techniques and algorithms.
        Building on this foundation, I then enrolled in the "Deep Learning A-Z" course, where I delved into the exciting world of deep learning and gained a thorough understanding of neural networks and their applications.
        Finally, I completed the "Artificial Intelligence A-Z" course, further enhancing my knowledge and skills in the field of AI. These courses not only provided me with a strong theoretical understanding, but also equipped me with the practical skills needed to apply these concepts to real-world problems.
        Through my dedication to learning and my successful completion of these courses, I am confident in my ability to continue making meaningful contributions to the field of artificial intelligence.
      </p>
      <ul>
        <li>
          <a href="https://www.udemy.com/course/machinelearning/">
            Machine Learning A-Z, Udemy
          </a>
        </li>
        <li>
          <a href="https://www.udemy.com/course/deeplearning/">
            Deep Learning A-Z, Udemy
          </a>
        </li>
        <li>
          <a href="https://www.udemy.com/course/artificial-intelligence-az/">
            Artificial Intelligence A-Z, Udemy
          </a>
        </li>
      </ul>
    </div>
   </div>
   <div class="skills">
   <div class="section">
    <h2>Skills</h2>
    <ul>
      <li>Vue.js</li>
      <li>C#</li>
      <li>Go</li>
      <li>Python</li>
      <li>JavaScript</li>
      <li>Git</li>
      <li>Apache Cassandra</li>
      <li>JanusGraph</li>
      <li>Familiar with the following Python frameworks for machine learning, deep learning, and AI:
        <ul>
          <li>NumPy</li>
          <li>Pandas</li>
          <li>Scikit-learn</li>
          <li>TensorFlow</li>
          <li>PyTorch</li>
          <li>Keras</li>
        </ul>
      </li>
    </ul>
   </div>
</div>
   <div class="contact">
    <div class="section">
      <h2>Contact</h2>
      <ul>
        <li>Email: magnushaxen97@gmail.com</li>
        <li>Phone: +45 51 32 67 15</li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/magnushaxen/">www.linkedin.com/in/magnushaxen/</a></li>
      </ul>
    </div>
   </div>
  </div>
</template>

<script>
export default {
  name: 'CV',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

/* Add a nice font to the entire page */
body {
  font-family: 'Open Sans', sans-serif;
}

/* Center the page content */
.section {
  max-width: 800px;
  margin: 0 auto;
  text-align: justify;
  padding-top: 32px;
  padding-bottom: 32px;
}

/* Add a nice blue color to links */
a {
  color: #0077c9;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

/* Style the headings */
h1, h2, h3 {
  font-weight: bold;
  margin-top: 20px;
  margin-bottom: 10px;
}

/* Add some padding and a gray background color to the footer */
footer {
  padding: 20px;
  background-color: #f2f2f2;
  color: #999;
  text-align: center;
}

.intro, .publications, .online_courses, .contact {
  background-color: #fef1e4;
  opacity: 0.9;
}

.education, .work_experience, .skills {
  color: #fef1e4;
}

.contact {
  padding-bottom: 238px;
}


</style>
