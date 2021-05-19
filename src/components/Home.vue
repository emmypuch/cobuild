<template>
  <div class="home">
    <nav id="mainNav">
      <div class="logo">
        <a href="#">CoBuiLD</a>
      </div>
      <ul>
        <li><a href="#home" class="active">Home</a></li>
        <li><a href="#service">Services</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#skill">Skills</a></li>
        <li><a href="#testimonial">Testimonials</a></li>
        <li><a href="#map">Map</a></li>
      </ul>
    </nav>

    <section class="hero" id="home">
      <div class="header-hero">
        <h2>We're Building Your Future</h2>
        <div class="par">
          <p>Take a step towards the future of construction with Cobuild</p>
        </div>
        <div class="link">
          <a href="#">Get A Quote</a>
        </div>
      </div>
    </section>

    <section class="services" id="service">
      <div class="service-heading">
        <h3>Our Services</h3>
        <p>
          Duis sed odio sit amet nibh vulputate cursus a sit amet mauris morbi
          accumsan <br />
          ipsum velit. Nam nec tellus a odio tincidunt auctor a ornare odio.
        </p>
      </div>
      <div class="service-icons-container">
        <div class="icon-content">
          <div class="icon">
            <img src="/images/excavator.svg" alt="" />
          </div>
          <div class="icon-heading">
            <h5>Fast Operations</h5>
            <p>
              Cobuild impresses you with fully <br />
              responsiveness and highly <br />
              customization
            </p>
          </div>
        </div>

        <div class="icon-content">
          <div class="icon">
            <img src="/images/crane.png" alt="" />
          </div>
          <div class="icon-heading">
            <h5>Fast Operations</h5>
            <p>
              Cobuild impresses you with fully <br />
              responsiveness and highly <br />
              customization
            </p>
          </div>
        </div>

        <div class="icon-content">
          <div class="icon">
            <img src="/images/helmet.svg" alt="" />
          </div>
          <div class="icon-heading">
            <h5>Fast Operations</h5>
            <p>
              Cobuild impresses you with fully <br />
              responsiveness and highly <br />
              customization
            </p>
          </div>
        </div>

        <div class="icon-content">
          <div class="icon">
            <img src="/images/skyline.png" alt="" />
          </div>
          <div class="icon-heading">
            <h5>Fast Operations</h5>
            <p>
              Cobuild impresses you with fully <br />
              responsiveness and highly <br />
              customization
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="work" id="work">
      <div class="work-heading">
        <h3>Featured Work</h3>
        <p>
          Duis aute irure dolor in reprehenderit volupte velit esse cillum
          fugiat
          <br />
          pariature occaecat cupidatat proident culpa.
        </p>
      </div>
      <div class="work-image-container">
        <div class="image-content">
          <img src="/images/1.jpeg" alt="" class="image" />
          <div class="image-link"></div>
        </div>

        <div class="image-content">
          <img src="/images/2.jpeg" alt="" class="image" />
          <div class="image-link"></div>
        </div>

        <div class="image-content">
          <img src="/images/3.jpeg" alt="" class="image" />
          <div class="image-link"></div>
        </div>

        <div class="image-content">
          <img src="/images/4.jpeg" alt="" class="image" />
          <div class="image-link"></div>
        </div>

        <div class="image-content">
          <img src="/images/5.jpeg" alt="" class="image" />
          <div class="image-link"></div>
        </div>

        <div class="image-content">
          <img src="/images/6.jpeg" alt="" class="image" />
          <div class="image-link"></div>
        </div>
      </div>
    </section>

    <section class="skill" id="skill">
      <div class="skill-container">
        <div class="skill-heading">
          <h4>
            We are expert in this field <br />
            since almost 20 years.
          </h4>
          <p>
            Proin gravida nibh vel velit auctor aliquet aenean sollicitudin,
            <br />
            lorem quis bibendum auctor, nisi elit cuat ipsum, nec sagittis
            <br />
            sem nibh id elit duis sed odio sit nibh vulputate cursus a sit amet
            <br />
            mauris morbi accumsan.
          </p>
        </div>

        <div class="skill-progress">
          <div class="skill-list">
            <li>
              <div
                class="wrap"
                style="display: flex; justify-content: space-between"
              >
                <h6>Buildings</h6>
                <h6>80%</h6>
              </div>
              <span class="bar"><span class="building"></span></span>
            </li>

            <li>
              <div
                class="wrap"
                style="display: flex; justify-content: space-between"
              >
                <h6>Architecture</h6>
                <h6>60%</h6>
              </div>
              <span class="bar"><span class="archi"></span></span>
            </li>

            <li>
              <div
                class="wrap"
                style="display: flex; justify-content: space-between"
              >
                <h6>Constructions</h6>
                <h6>50%</h6>
              </div>
              <span class="bar"><span class="constru"></span></span>
            </li>

            <li>
              <div
                class="wrap"
                style="display: flex; justify-content: space-between"
              >
                <h6>Planning</h6>
                <h6>40%</h6>
              </div>
              <span class="bar"><span class="planning"></span></span>
            </li>
          </div>
        </div>
      </div>
    </section>

    <section class="testimonial" id="testimonial">
      <h3>fsjhfjfgs</h3>
    </section>

    <section class="map" id="map">
      <h3>fsjhfjfgs</h3>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      msg: "Hello world",
    };
  },
  mounted() {
    window.addEventListener("scroll", function() {
      const logo = document.querySelectorAll(".logo")[0];
      const mainNav = document.querySelector("#mainNav");

      if (window.pageYOffset > 0) {
        logo.style.height = "64px";
        mainNav.classList.add("bg-yellow");
        mainNav.classList.add("txt-white");
      } else {
        logo.style.height = "84px";
        mainNav.classList.remove("bg-yellow");
        mainNav.classList.remove("txt-white");
      }
    });
  },
};
</script>

<style scoped>
nav#mainNav {
  display: flex;
  justify-content: space-between;
  padding: 1em 7em;
  position: fixed;
  width: 100%;
  top: 0px;
  background: #fff;
  transition: background 0.4s;
}

nav#mainNav .logo {
  font-size: 1.5em;
  transition: height 0.4s;
  height: 84px;
  padding-top: 0.9em;
}

nav#mainNav .logo a {
  /* color: #F5AF00 !important; */
  transition: color 0.4s;
  color: #f5af00;
  text-decoration: none;
}

.bg-yellow {
  background: #f5af00 !important;
}

.txt-white a {
  color: #fff !important;
}

.txt-white a:hover {
  color: #000 !important;
}

nav#mainNav ul {
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 500px;
}

nav#mainNav ul li a {
  text-decoration: none;
  transition: color 0.4s;
  font-weight: 200;
  font-size: 0.8em;
  color: #000;
  text-transform: uppercase;
}

nav#mainNav ul li a:hover {
  color: #f5af00;
}

@media screen and (max-width: 768px) {
  nav#mainNav {
    padding: 1.4em;
  }

  nav#mainNav ul {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
  }
}

/* Section styling */

section:nth-of-type(1) {
  margin-top: 84px;
}

section {
  height: 300px;
  padding: 16px;
}

section:nth-of-type(odd) {
  background: #eee;
}

section.hero {
  padding: 15em 7em;
  display: flex;
  justify-content: center;
  vertical-align: center;
  align-items: center;
}

section.hero h2 {
  padding-top: 1em;
  font-size: 4rem;
  color: #222;
  font-weight: 300;
  line-height: 2px;
  letter-spacing: 2px;
}

div.par p {
  text-align: center;
  margin-top: 4em;
  font-size: 1.2rem;
  color: #999;
  font-weight: 300;
  letter-spacing: 1px;
}

div.link {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 3em;
}

div.link a {
  text-decoration: none;
  font-weight: 300;
  line-height: 2px;
  letter-spacing: 1px;
  font-size: 0.8rem;
  text-transform: uppercase;
  background: #f5af00;
  color: #fff;
  padding: 20px 35px;
  border: 2px solid #f5af00;
  border-radius: 50px;
  outline: none;
  text-align: center;
  transition: background 0.4s;
}

div.link a:hover {
  background: #222;
  color: #fff;
  border: 2px solid #222;
}

/* Services styling */

section.services {
  padding-top: 5rem;
  padding-left: 6rem;
  padding-right: 6rem;
  padding-bottom: 25rem;
}

div.service-heading h3,
div.work-heading h3 {
  text-align: center;
  font-size: 2.3rem;
  font-weight: 300;
  letter-spacing: 1px;
  color: #222;
}

div.service-heading p,
div.work-heading p {
  text-align: center;
  font-size: 0.9rem;
  font-weight: 200;
  padding-top: 1.2rem;
  color: #999;
}

div.service-icons-container {
  margin: 3rem;
  padding-top: 2rem;
  display: flex;
  justify-content: space-between;
}

div.icon {
  text-align: center;
}

div.icon img {
  width: 60px;
}

div.icon-heading h5 {
  color: #222;
  font-size: 1.1rem;
  font-weight: 400;
  letter-spacing: 1px;
  padding-top: 1rem;
  text-align: center;
}

div.icon-heading p {
  color: #999;
  font-size: 0.8rem;
  padding-top: 1rem;
}

/* Work styling */

section.work {
  padding-top: 5rem;
  padding-left: 6rem;
  padding-right: 6rem;
  padding-bottom: 65rem;
}

div.work-image-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
}

div.image-content {
  width: 50%;
  margin: 1rem;
}

div.image-content img {
  width: 380px;
  height: auto;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: 0.5s ease;
  backface-visibility: hidden;
}

div.image-link {
  transition: 0.5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}

div.image-content:hover .image {
  opacity: 0.3;
}

div.image-content:hover div.image-link {
  opacity: 1;
}

/* Skill Styling */

div.skill-heading h4 {
  font-weight: 400;
  font-size: 2.5rem;
  letter-spacing: 1px;
  color: #222;
}

div.skill-heading p {
  font-weight: 300;
  font-size: 1.1rem;
  color: #999;
  padding-top: 2rem;
}

section.skill {
  padding-top: 5rem;
  padding-left: 6rem;
  padding-right: 6rem;
  padding-bottom: 20rem;
}

div.skill-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}

div.skill-list li {
  margin: 20px 0;
  list-style: none;
}

.bar {
  display: block;
  height: 10px;
  border: 1px solid #222;
  border-radius: 5px;
  overflow: hidden;
  border: 1px solid #eee;
}

.bar span {
  height: 10px;
  background: #f5af00;
  float: left;
}

.building {
  width: 80%;
  animation: building 2s;
}

.archi {
  width: 60%;
  animation: archi 2s;
}

.constru {
  width: 50%;
  animation: constru 2s;
}

.planning {
  width: 40%;
  animation: planning 2s;
}

@keyframes building {
  0% {
    width: 0%;
  }

  100% {
    width: 80%;
  }
}

@keyframes archi {
  0% {
    width: 0%;
  }

  100% {
    width: 60%;
  }
}

@keyframes constru {
  0% {
    width: 0%;
  }

  100% {
    width: 50%;
  }
}

@keyframes planning {
  0% {
    width: 0%;
  }

  100% {
    width: 40%;
  }
}

div.wrap h6 {
  font-weight: 300;
  text-transform: uppercase;
  font-size: 0.8rem;
  padding-bottom: 1rem;
}

/* Responsiveness Styling */

@media screen and (max-width: 768px) {
  section.hero {
    padding: 15em 0.4em;
  }

  section.hero h2 {
    padding-top: 1em;
    font-size: 2.2rem;
    line-height: 0;
    letter-spacing: 0;
    text-align: center;
  }

  div.par p {
    font-size: 0.9rem;
    line-height: 0;
    letter-spacing: 0;
  }

  /* services    */
  section.services {
    padding-top: 5rem;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-bottom: 65rem;
  }

  div.service-heading h3,
  div.work-heading h3 {
    font-size: 2rem;
  }

  div.service-heading p,
  div.work-heading p {
    font-size: 0.587rem;
  }

  div.service-icons-container {
    margin: 1rem;
    padding-top: 2rem;
    display: flex;
    flex-direction: column;
  }

  div.icon-content {
    padding-bottom: 3rem;
  }

  div.icon {
    text-align: center;
  }

  div.icon img {
    width: 60px;
  }

  div.icon-heading h5 {
    font-size: 1.2rem;
  }

  div.icon-heading p {
    text-align: center;
  }

  /* work */

  section.work {
    padding-top: 5rem;
    padding-left: 0;
    padding-right: 0;
    padding-bottom: 110rem;
  }

  div.work-image-container {
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  div.image-content {
    /* position: relative; */
    width: 70%;
    margin: 0.8rem;
  }

  div.image-content img {
    width: 300px;
  }

  /* Skills */

  section.skill {
    padding-top: 5rem;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-bottom: 30rem;
  }

  div.skill-container {
    display: flex;
    flex-direction: column;
  }

  div.skill-heading h4 {
    font-size: 1.5rem;
    text-align: center;
  }

  div.skill-heading p {
    font-size: 0.7rem;
    text-align: center;
  }

  div.skill-progress {
    padding-top: 1.2rem;
  }
}

@media screen and (max-width: 424px) {
  section.hero {
    padding: 15em 0.2em;
  }

  section.hero h2 {
    font-size: 1.7rem;
  }

  div.par p {
    font-size: 0.8rem;
  }

  /* Work */

  section.work {
    padding-top: 5rem;
    padding-left: 0;
    padding-right: 0;
    padding-bottom: 300rem;
  }

  div.image-content {
    width: 125%;
  }

  div.image-content img {
    width: 310px;
  }

  div.work-heading p {
    font-size: 0.585rem;
  }
}

@media screen and (max-width: 400px) {
  section.hero {
    padding: 15em 0.2em;
  }

  section.hero h2 {
    font-size: 1.5rem;
  }

  div.par p {
    font-size: 0.6rem;
  }

  /* services */
  section.services {
    padding-bottom: 60rem;
  }

  div.service-heading h3 {
    font-size: 1.7rem;
  }

  div.icon-heading h5 {
    font-size: 1.1rem;
  }

  div.icon-heading p {
    font-size: 0.6rem;
  }

  /* Work */

  section.work {
    padding-top: 5rem;
    padding-left: 0;
    padding-right: 0;
    padding-bottom: 85rem;
  }

  div.image-content {
    width: 70%;
  }

  div.image-content img {
    width: 220px;
  }

  div.work-heading p {
    font-size: 0.585rem;
  }

  div.work-heading h3 {
    font-size: 0.9rem;
  }

  div.work-heading p {
    font-size: 0.5rem;
  }

  /* skills */

  section.skill {
    padding-top: 5rem;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-bottom: 30rem;
  }

  div.skill-heading h4 {
    font-size: 1.2rem;
  }

  div.skill-heading p {
    font-size: 0.5rem;
  }
}
</style>
