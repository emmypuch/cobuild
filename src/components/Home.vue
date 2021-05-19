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
                Duis sed odio sit amet nibh vulputate cursus a sit amet mauris morbi accumsan <br> ipsum velit. Nam nec tellus a odio tincidunt auctor a ornare odio.
            </p>
            </div>
            <div class="service-icons-container">
                <div class="icon-content">
                    <div class="icon">
                        <img src="/images/excavator.svg" alt="">
                    </div>
                    <div class="icon-heading">
                        <h5>Fast Operations</h5>
                        <p>Cobuild impresses you with fully <br> responsiveness and highly <br> customization</p>
                    </div>
                </div>

                <div class="icon-content">
                    <div class="icon">
                        <img src="/images/crane.png" alt="">
                    </div>
                    <div class="icon-heading">
                        <h5>Fast Operations</h5>
                        <p>Cobuild impresses you with fully <br> responsiveness and highly <br> customization</p>
                    </div>
                </div>

                <div class="icon-content">
                    <div class="icon">
                        <img src="/images/helmet.svg" alt="">
                    </div>
                    <div class="icon-heading">
                        <h5>Fast Operations</h5>
                        <p>Cobuild impresses you with fully <br> responsiveness and highly <br> customization</p>
                    </div>
                </div>

                <div class="icon-content">
                    <div class="icon">
                        <img src="/images/skyline.png" alt="">
                    </div>
                    <div class="icon-heading">
                        <h5>Fast Operations</h5>
                        <p>Cobuild impresses you with fully <br> responsiveness and highly <br> customization</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="work" id="work">
            <h3>fsjhfjfgs</h3>
        </section>

        <section class="skill" id="skill">
            <h3>fsjhfjfgs</h3>
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
            msg: "Hello world"
        }
    },
    mounted() {
        window.addEventListener("scroll", function() {
            const logo = document.querySelectorAll(".logo")[0];
            const mainNav = document.querySelector("#mainNav");

            if(window.pageYOffset > 0) {
                logo.style.height = "64px";
                mainNav.classList.add('bg-yellow');
                mainNav.classList.add('txt-white');
            } else {
                logo.style.height = "84px";
                mainNav.classList.remove('bg-yellow');
                mainNav.classList.remove('txt-white');
            }
        });
    }
}
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
    color: #F5AF00;
    text-decoration: none;
}

.bg-yellow {
    background: #F5AF00 !important;
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
    color: #F5AF00;
}

@media screen and (max-width:768px) {
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
    background: #F5AF00;
    color: #fff;
    padding: 20px 35px;
    border: 2px solid #F5AF00;
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

div.service-heading h3 {
    text-align: center;
    font-size: 2.3rem;
    font-weight: 300;
    letter-spacing: 1px;
    color: #222;
}

div.service-heading p {
    text-align: center;
    font-size: 0.9rem;
    font-weight: 300;
    letter-spacing: 1px;
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
    letter-spacing: 1px;
    padding-top: 1rem;
    text-align: center;
}

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
}

@media screen and (max-width: 350px) {
    section.hero {
        padding: 15em 0.2em; 
    }

    section.hero h2 {
        font-size: 1.2rem;
    }

    div.par p {
        font-size: 0.6rem;
    }
}
</style>