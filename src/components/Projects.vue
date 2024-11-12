<template>
    <div id="wrapper3">
        <h2 v-motion
            :initial="{
                opacity: 0,
            }"
            :visibleOnce="{
                opacity: 1,
                transition: {
                delay:400,
                duration: 500,
                ease: 'easeInOut'
                },
            }" class="mb-5"><span>03.</span> Projects</h2>
        <div id="content-wrapper" class="">
            <div class="row m-0">

                <div v-motion
            :initial="{
                opacity: 0,
                y:50
            }"
            :visibleOnce="{
                opacity: 1,
                y:0,
                transition: {
                delay:200,
                duration: 500,
                ease: 'easeInOut'
                },
            }" id="column" class="col-12 col-lg-4 p-4">
            <div>
                <div id="image-div" class="rounded-3 ">
                        <img class="img-fluid rounded-3" src="../assets/LoginSignup.PNG" alt="Login Page">
                    </div>
                        <h3>Signin And Signup Website</h3>
                        <p>My sign in and sign up website made using html, javascript and css. Also, integrated with bootstrap for the responsiveness of it.</p>
            </div>


                    <div id="links">
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://jeffreyromerosa.github.io/login-signup-page/signin.html">Live Demo</a></div>
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://github.com/JeffreyRomerosa/login-signup-page">GitHub Repo</a></div>
                    </div>
                </div>

                <!-- <div v-motion
            :initial="{
                opacity: 0,
                y:50
            }"
            :visibleOnce="{
                opacity: 1,
                y:0,
                transition: {
                delay:300,
                duration: 500,
                ease: 'easeInOut'
                },
            }" id="column" class="col-12 col-lg-4 p-4 mb-4">
                    <div>
                        <div id="image-div" class="rounded-3">
                                <img class="img-fluid rounded-3" src="../assets/comments.png" alt="portfolio">
                            </div>
                            <h3>Interactive comments</h3>
                            <p>This was a project I worked on together with my talented friend <a id="collab" href="https://github.com/Gerald-006">Gerald Jackson</a>. A fullstack social media app in which users can create their own accounts and be able to post, update and delete their comments as well as reply to other people's comments. The frontend was done using Vuejs and the backend using Ruby on Rails</p>

                    </div>

                    <div id="links">
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://interactive-comments-a6k7.onrender.com/home/60">Live Demo</a></div>
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://github.com/MuchiriAndrew/Interactive-Comments-Section">GitHub Repo</a></div>
                    </div>
                </div> -->

                <div v-motion
            :initial="{
                opacity: 0,
                y:50
            }"
            :visibleOnce="{
                opacity: 1,
                y:0,
                transition: {
                delay:200,
                duration: 500,
                ease: 'easeInOut'
                },
            }" id="column" class="col-12 col-lg-4 p-4">
                    <div>
                        <div id="image-div" class="rounded-3">
                                <img class="img-fluid rounded-3" src="../assets/portfolio bootstrap.PNG" alt="portfolio">
                            </div>
                            <h3>Portfolio 1.0</h3>
                            <p>This is my first portfolio website made using html, css, and bootstrap.</p>
                    </div>

                    <div id="links">
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://portfolio-in-bootstrap.vercel.app/">Live Demo</a></div>
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://github.com/JeffreyRomerosa/Portfolio-In-Bootstrap">GitHub Repo</a></div>
                    </div>
                </div>

                <div v-motion
            :initial="{
                opacity: 0,
                y:50
            }"
            :visibleOnce="{
                opacity: 1,
                y:0,
                transition: {
                delay:400,
                duration: 500,
                ease: 'easeInOut'
                },
            }" id="column" class="col-12 col-lg-4 p-4">
                    <div>
                        <div id="image-div" class="rounded-3">
                                <img class="img-fluid rounded-3" src="../assets/Weather Application.JPG" alt="portfolio">
                            </div>
                            <h3>Weather Application With API</h3>
                            <p>This weather application utilizes the OpenWeatherMap API to fetch and display real-time weather data, including temperature, humidity, wind speed, and weather conditions. The app provides an easy-to-use interface, allowing users to search for weather details by city or location.</p>
                    </div>

                    <div id="links">
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://portfolio-in-bootstrap-ngtu.vercel.app/">Live Demo</a></div>
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://github.com/JeffreyRomerosa/Weather-Application">GitHub Repo</a></div>
                    </div>
                </div>
            </div>

            <!-- <div class="row m-0">


                <div v-motion
            :initial="{
                opacity: 0,
                y:50
            }"
            :visibleOnce="{
                opacity: 1,
                y:0,
                transition: {
                delay:300,
                duration: 500,
                ease: 'easeInOut'
                },
            }" id="column" class="col-12 col-lg-4 p-4">
                    <div>
                            <div id="image-div" class="rounded-3">
                                <img class="img-fluid rounded-3" src="../assets/space.jpg" alt="portfolio">
                            </div>
                            <h3>Space Tourism Website</h3>
                            <p>A multi-page space tourism website done using React, Bootstrap and Framer Motion for the subtle animations. A purely frontend project that challenged my skills in React Router and State Management.</p>
                    </div>

                    <div id="links">
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://space-tourism-lxuk.onrender.com/">Live Demo</a></div>
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://github.com/MuchiriAndrew/Space-Tourism">GitHub Repo</a></div>
                    </div>
                </div>

                <div v-motion
            :initial="{
                opacity: 0,
                y:50
            }"
            :visibleOnce="{
                opacity: 1,
                y:0,
                transition: {
                delay:400,
                duration: 500,
                ease: 'easeInOut'
                },
            }" id="column" class="col-12 col-lg-4 p-4">
                    <div>
                            <div id="image-div" class="rounded-3">
                                <img class="img-fluid rounded-3" src="../assets/ecommerce.jpg" alt="portfolio">
                            </div>
                            <h3>E-Commerce Product Page</h3>
                            <p>Another noteworthy frontend project done using Vuejs and Bootstrap. Challenged me to work with cart functionality, using the local storage function in JavaScript and Bootstrap's Modal for the lightbox gallery</p>
                    </div>

                    <div id="links">
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://product-page-an5n.onrender.com">Live Demo</a></div>
                        <div class="rounded-3" id="btns"><a target="_blank" href="https://github.com/MuchiriAndrew/Front-End-Projects/tree/master/e-commerce%20product%20page">GitHub Repo</a></div>
                    </div>
                </div>
            </div> -->
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#wrapper3 {
    background: #0a192f;
    min-height: 100vh;
    height: max-content;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: start;
}

#content-wrapper {
    width: 90%;
    height: max-content;
}

.row {
    width: 100%;
}

#wrapper3 h2 {
    width: 90%;
    text-align: start;
    font-size: 26px;
    color: hsl(239, 57%, 85%);
}
#wrapper3 h2 span {
    color: #64ffda;
    font-size: 26px;
}

#wrapper3 h2 b {
    color: #64ffda;
}

#column {
    min-height: 500px;
    height: max-content;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px; */
}

#column h3 {
    font-family: Poppins;
    font-size: 24px;
    color: hsl(239, 57%, 85%);
}

#column p {
    font-family: Poppins;
    font-size: 12px;
    color: hsl(223, 19%, 93%);
}

#image-div {
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
     margin-bottom: 10px;
}
/* #image-div:hover {
    scale: 1.05;
    transition: 0.8s ease-in-out;
} */
#links {
    display: flex;
    justify-content: space-around;
    flex-direction: row;
}

#btns {
    width: 100px;
    height: 50px;
    border: 1px solid #64ffda;
}
#btns a {
    text-decoration: none;
    color: #64ffda;
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

#btns:hover {
    background: #64ffda;
    transition: 0.3s ease-in-out;
    cursor: pointer;
}

#btns a:hover{
    color: #0a192f;
    transition: 0.3s ease-in-out;
}

#collab {
    font-size: 12px;
    font-family: Poppins;
    text-decoration: none;
    color: #64ffda;
    /* display: inline-block; */
    position: relative;
}

#collab::after {
  content: '';
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #65ffda;
  transform-origin: bottom right;
  transition: transform 0.3s ease-out;
}

#collab:hover::after {
    transform: scaleX(1);
    transform-origin: bottom left;
}

@media (max-width: 992px) and (min-width: 768px) {
    #column {
    min-height: 650px;
    height: max-content;
    display: flex;
    flex-direction: column;
}
#image-div:hover {
    scale: unset;
    transition: unset;
}
}

@media (max-width: 768px){
    #column {
    min-height: 500px;
    height: max-content;
    display: flex;
    flex-direction: column;
}

#image-div:hover {
    scale: unset;
    transition: unset;
}

#links {
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    flex-grow: 1;
    align-items: center;
}
}

</style>
