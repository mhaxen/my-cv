<template>
  <div class="cv"> 
   <div class="headline">
    <h1>Magnus Haxen</h1>
   </div>
   <div class="intro section">
    <h2>Hi there!</h2>
    <p>
      My name is Magnus Haxen, and I am a huge enthusiast of deep learning and artificial intelligence. I recently graduated from Aarhus University with a Bachelor's degree in Computer Science, where I focused on AI and deep learning as part of my studies.
      During my time at Aarhus University, I had the opportunity to learn from some of the leading experts in the field and work on various projects that allowed me to apply my knowledge in a practical setting. I also had the unique experience of completing half of my degree during the pandemic, which presented its own set of challenges but ultimately helped me to become even more resilient and adaptable.
      In my free time, you can find me staying up-to-date on the latest research and developments within the field of AI and deep learning. My ultimate career goal is to land a job at a well-respected company where I can put my skills and passion to good use and make a positive impact in the world of artificial intelligence. With my dedication, drive, and now a solid foundation in computer science and AI, I am confident that I can achieve this dream and more.
    </p>
   </div>
   <div class="education section">
    <h3>Education</h3>
    <ul>
      <li>
        Bachelor's Degree in Computer Science, Institution, 2021
      </li>
    </ul>
   </div>
   <div class="publications section">
    <h3>Publications</h3>
    <ul>
      <li>
        <a href="https://dl.acm.org/doi/10.1145/3459637.3482072">
          "Center Point Query Authentication", CIKM2021 conference, 2021
        </a>
      </li>
    </ul>
   </div>
   <div class="work_experience section">
    <h3>Work Experience</h3>
    <ul>
      <li>
        Software Developer, Startup Company, 2021-2022
      </li>
    </ul>
   </div>
   <div class="online_courses section">
    <h3>Online Courses</h3>
    <ul>
      <li>
        Machine Learning, Institution, Year
      </li>
      <li>
        Deep Learning, Institution, Year
      </li>
      <li>
        AI, Institution, Year
      </li>
    </ul>
   </div>
   <div class="skills section">
  <h3>Skills</h3>
  <ul>
    <li>Vue.js</li>
    <li>C#</li>
    <li>Go</li>
    <li>Python</li>
    <li>JavaScript</li>
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
   <div class="contact section">
    <h3>Contact</h3>
    <ul>
      <li>Email: magnushaxen97@gmail.com</li>
      <li>Phone: +45 51 32 67 15</li>
      <li>LinkedIn: <a href="https://www.linkedin.com/in/magnushaxen/">www.linkedin.com/in/magnushaxen/</a></li>
    </ul>
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
  color: #333;
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


</style>