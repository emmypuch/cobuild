<template>
    <div class="home">
        <nav id="mainNav">
            <div class="logo">
                <a href="#">CoBuild</a>
            </div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Work</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">testimonials</a></li>
                <li><a href="#">Map</a></li>
            </ul>
        </nav>

        <section class="hero" id="hero">
            <h3>fkjhnsjfgdsfsfg k</h3>
        </section>

        <section class="services" id="services">
            <h3>fsjhfjfgs</h3>
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
    }
}
</script>


<style scoped>
nav#mainNav {
    display: flex;
    justify-content: space-between;
    padding: 0px 16px;
    position: fixed;
    width: 100%;
    top: 0px;
    background: #fff;
    transition: background 0.4s;
}

nav#mainNav .logo {
    font-size: 1.3em;
    transition: font-size 0.4s;
}

nav#mainNav ul {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 400px;
}

nav#mainNav ul li a {
    text-decoration: none;
    transition: color 0.4s;
    font-weight: 300;
    font-size: 1em;
    color: #000;
}

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
</style>