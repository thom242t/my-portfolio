<template>
  <div class="main-wrapper">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top" id="sideNav">
    <a class="navbar-brand js-scroll-trigger" href="#page-top">
      <span class="d-block d-lg-none">Thomas Skov Moeslund</span>
      <span class="d-none d-lg-block">
       
      </span>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link js-scroll-trigger" href="#about">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll-trigger" href="#experience">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll-trigger" href="#education">Contacts</a>
        </li>
      </ul>
    </div>
  </nav>

  <div class="container-fluid p-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
      <div class="w-100">
        <h1 class="mb-0">Thomas Skov
          <span class="text-primary">Moeslund</span>
        </h1>
        <br>
        <h3 class="mb-0">Web developer and Designer</h3>
        <br>
        <div class="subheading mb-5">Spangsbjerg kirkevej, Esbjerg V 6710, Denmark · +45 42 70 25 20 ·
          <a href="thomas_skov@yahoo.com">thomas_skov@yahoo.com</a>
        </div>
        <p class="lead mb-5">Welcome to my portfolio, I am a student studying
                            multimedia design and
                            communication, with a focus on
                            web development and design. I
                            have lived in different and studied
                            international my entire life.
                            I thrive in a group setting when it comes to projects, 
                            but I am very capable working independtly.
        </p>
        
      </div>
    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex justify-content-center" id="experience">
      <div class="w-100">
        <h2 class="mb-5">Projects</h2>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
          <div class="resume-content">
            <h3 class="mb-0">Educational Space website</h3>
            <div class="subheading mb-3">Web development and Design</div>
            <p>A website made with Html and SASS.</p>
          </div>
          <br>               
          <div class="resume-date text-md-right">
            <span class="text-primary">December 2018</span>
          </div>
        </div>
                <div id="readmoretoggle">
                      <v-btn id="readmore" v-on:click="toggleshow" medium color="error">View</v-btn>
                      <p v-show="toggle" style="background-color:">
                        <br>
                        This was my first exam project which was completed at Business academy southwest. 
                        The goal was to make a website that would be published by a danish sciene magazine, 
                        our idea was to make a educational website for a younger target audience and aimed
                        for to be interactive. We made all the planets with adobe illustrator because we wanted
                        it to appeal more to our target audience. The stars in the background are actually moving
                        upwards and this design was made so that our website looked like it was more interactive and 
                        gave the website a dynamic aesthetic. We found the code for it online. The group and made apprioate
                        business models that would help us push the website to the target audience, like a gantt chart, 
                        shannon weaver model, communication theory and a SWOT analysis. For it being my first 
                        big project to complete I am very satisfied with the result but I am also aware of the changes 
                        I should make in the future.  
                        <br>
                        <br>
                        <v-img :src="require('@/assets/space_site.png')"></v-img>
                        <br>
                        
                      </p>
                </div>
                  <br>
                  <br>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
          <div class="resume-content">
            <h3 class="mb-0">Double Exposure</h3>
            <div class="subheading mb-3">Adobe Photoshop</div>
            <p>A picture of me made in photoshop and using the technique of double exposure. 
            </p>
          </div>
          <div class="resume-date text-md-right">
            <span class="text-primary">Feburary 2019</span>
          </div>
        </div>
                <div id="readmoretoggle">
                      <v-btn id="readmore" v-on:click="toggleshow1" medium color="error">View</v-btn>
                      <p v-show="toggle1" style="background-color:">
                        <br>
                         In photography and cinematography, a multiple exposure is the superimposition of
                         two or more exposures to create a single image, and double exposure has a corresponding
                          meaning in respect of two images. The exposure values may or may not be identical 
                          to each other. Using photoshop I created a layer mask on my on the original image and 
                          decreased the opacity. I created a layer mask on the background and started to take away
                          some of it using the brush tool.
                        <br>
                         <v-img :src="require('@/assets/inmyhead.jpg')"></v-img>
                        <br>

                    </p>
                </div>
                  <br>
                  <br>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
          <div class="resume-content">
            <h3 class="mb-0">Advertisement for EASV</h3>
            <div class="subheading mb-3">Video Editing and Marketing</div>
            <p>A video that was made to advertise the school EASV.
            </p>
          </div>
          <div class="resume-date text-md-right">
            <span class="text-primary">March 2019</span>
          </div>
        </div>
                <div id="readmoretoggle">
                      <v-btn id="readmore" v-on:click="toggleshow2" medium color="error">View</v-btn>
                      <p v-show="toggle2">
                        <br>
                        We were given the task of developing a method to attract more students to come and 
                      study at EASV. The group and I, of 4 people, decided to make a promo video that highlights the 
                      city a little and the school. This would give people a better idea of what kind of institution 
                      they would be coming to. We decided to use a teacher as a voiceover, to add a personal touch to
                      the video, and it was important to us that the teacher had confidence and good english. 
                      A section of this project was also being able to present the video and its concept to the 
                      marketing coordinator of Business Academy Southwest, and if the concept proved to be sufficient 
                      she would use it.
                      <br>
                      <br>
                      
                       <iframe width="100%" height="470"
                        src="https://www.youtube.com/embed/nEFEFrF6Cpc" 
                        frameborder="0" allow="accelerometer; autoplay; encrypted-media;> gyroscope; picture-in-picture" allowfullscreen>
                       </iframe>
                       
                       <br>
                      </p>
                </div>
                  <br>
                  <br>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
          <div class="resume-content">
            <h3 class="mb-0">Browser Game</h3>
            <div class="subheading mb-3">Web development</div>
            <p>A browser game made with Vuejs framework.
            </p>
          </div>
          <div class="resume-date text-md-right">
            <span class="text-primary">March 2019</span>
          </div>
        </div>
         <div id="readmoretoggle">
                      <v-btn id="readmore" v-on:click="toggleshow3" medium color="error">View</v-btn>
                      <p v-show="toggle3" style="background-color:">
                        <br>
                        I made this browser game using vuejs as a framework, trying to use functions on a base level.
                        It's a game with 2 buttons, where the goal is to beat up a pikachu. This is also using if/else 
                        statements and targeting specific objects with javascript to create the effect of img change and 
                        and the health bar showing a decrease. 
                        <br>  
                        <br>
                        <img id="pika1" src="@/assets/pika1.png" height="300" alt="">
                        <img id="pika2" src="@/assets/pika2.png" height="300" alt="">
                    </p>
                </div>
                  <br>
                  <br>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
          <div class="resume-content">
            <h3 class="mb-0">Climbing Informercial</h3>
            <div class="subheading mb-3">User Experience</div>
            <p>
              An informercial made for a real business 
            </p>
          </div>
          <div class="resume-date text-md-right">
            <span class="text-primary">April 2019</span>
          </div>
        </div>
         <div id="readmoretoggle">
               <v-btn id="readmore" v-on:click="toggleshow4" medium color="error">View</v-btn>
                  <p v-show="toggle4" style="background-color:">
                        <br>
                        This was a video that was made to be a informercial about a climbing gym
                        in Esbjerg where we wanted to advertise the gym to beginners. We wanted to 
                        have some stylish b-roll and show off the gym to catch the attention of the viewer.
                        We had a interview with the manager of the gym so that the viewers would get an insight
                        on what the manager's opinions are and so that the viewer would like the gym is a 
                        more down to earth kind of place.
                        <br>
                        <br>
                  
                        <iframe width="100%" height="600"
                        src="https://www.youtube.com/embed/qrl1MVaomnA"
                         frameborder="0" allow="accelerometer; autoplay; encrypted-media;> gyroscope; picture-in-picture" allowfullscreen>
                        </iframe>
                   
                  </p>
         </div>
                  <br>
                  <br>

      </div>

    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="education">
      <div class="w-100">
        <h2 class="mb-5">Resume</h2>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5">
          <div class="resume-content">
            <h3 class="mb-0">CV</h3>
            <div id=cvlink class="subheading mb-3">
              <a href="https://drive.google.com/open?id=1ZgezfxrzT5MVoGuCT8Da4l0rxpGRrkgM">view here</a>
            </div>
            <div></div>
            <p></p>
          </div>
          <div class="resume-date text-md-right">
            <span class="text-primary"></span>
          </div>
        </div>

        <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
          <div class="resume-content">
            <h3 class="mb-0">Business Card</h3>
            <div id="cvlink"  class="subheading mb-3">
              <a href="https://drive.google.com/open?id=1GpQ3CsjRubMNp3PmdrO_7SlblINgSWWl">view here</a>
              </div>
            <p></p>
          </div>
          <div class="resume-date text-md-right">
            <span class="text-primary"></span>
          </div>
        </div>

      </div>
      
    </section>

    <hr class="m-0">

  </div>

  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'My portfolio',
      toggle: false,
      toggle1: false,
      toggle2: false,
      toggle3: false,
      toggle4: false,
    }
  },
  mounted () {
    this.$nextTick(() => {
      // our custom jQuery code goes here
    })
  },
  
methods: {
    toggleshow() {
     this.toggle = !this.toggle
    },
     toggleshow1() {
     this.toggle1 = !this.toggle1
    }, toggleshow2() {
     this.toggle2 = !this.toggle2
    },
     toggleshow3() {
     this.toggle3 = !this.toggle3
    },
     toggleshow4() {
     this.toggle4 = !this.toggle4
    },
  },
};


</script>

<style>
template {
  scroll-behavior: smooth;
}
body {
  font-family: 'Muli' sans-serif, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  padding-top: 54px;
  color: #0D1B1E;
  background-color:#F5EFED;
}

.text-primary {
    color: #bf0603!important;
}

.bg-primary {
    background-color: #BF0603!important;
}

a {
  color:  #BF0603;
}

a:hover, a:focus, a:active {
  color: #824027;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family:'Muli Bold' sans-serif, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  font-weight: 700;
  text-transform: uppercase;
  color: #0D1B1E;
}

h1 {
  font-size: 6rem;
  line-height: 5.5rem;
}

h2 {
  font-size: 3.5rem;
}

h3 {
  font-size: 2rem;
}

p.lead {
  font-size: 1.15rem;
  font-weight: 400;
}

.subheading {
  text-transform: uppercase;
  font-weight: 500;
  font-family: 'Muli semibold' sans-serif, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  font-size: 1.5rem;
}


@media (min-width: 992px) {
  body {
    padding-top: 0;
    padding-left: 17rem;
  }
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family:'Muli Bold' sans-serif, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  font-weight: 700;
  text-transform: uppercase;
  color: #0D1B1E;
}

h1 {
  font-size: 6rem;
  line-height: 5.5rem;
}

h2 {
  font-size: 3.5rem;
}

h3 {
  font-size: 2rem;
}

p.lead {
  font-size: 1.15rem;
  font-weight: 400;
}

.subheading {
  text-transform: uppercase;
  font-weight: 500;
  font-family: 'Muli semibold' sans-serif, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  font-size: 1.5rem;
}

.social-icons a {
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: #495057;
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: #BF0603;
}

.dev-icons {
  font-size: 3rem;
}

.dev-icons .list-inline-item i:hover {
  color:  #BF0603;
}

#sideNav .navbar-nav .nav-item .nav-link {
  font-weight: 800;
  letter-spacing: 0.05rem;
  text-transform: uppercase;
  color: #F5EFED;
  
}

#sideNav .navbar-toggler:focus {
  outline-color:  #BF0603;
}

.iframe-container {
  overflow: hidden;
  padding-top: 56.25%;
  position: relative;
}
 
.iframe-container iframe {
   border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;
}
 
/* 4x3 Aspect Ratio */
.iframe-container-4x3 {
  padding-top: 75%;
}

@media (min-width: 992px) {
  #sideNav {
    text-align: center;
    position: fixed;
    top: 0;
    left: 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 17rem;
    height: 100vh;
  }
  #sideNav .navbar-brand {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin: auto auto 0;
    padding: 0.5rem;
  }
  #sideNav .navbar-brand .img-profile {
    max-width: 10rem;
    max-height: 10rem;
    border: 0.5rem solid #F5EFED;
  }
  #sideNav .navbar-collapse {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-box-flex: 0;
    -ms-flex-positive: 0;
    flex-grow: 0;
    width: 100%;
    margin-bottom: auto;
  }
  #sideNav .navbar-collapse .navbar-nav {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 100%;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item {
    display: block;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item .nav-link {
    display: block;
  }
}

#readmore {
  color: whitesmoke;
  background-color:  #BF0603 !important; 
}

#pika1 {
  float: left;;
}
#pika2 {
  right: 5vw;;
}


section.resume-section {
  padding-top: 5rem !important;
  padding-bottom: 5rem !important;
  max-width: 75rem;
}

section.resume-section .resume-item .resume-date {
  min-width: none;
}

@media (min-width: 768px) {
  section.resume-section {
    min-height: 100vh;
  }
  section.resume-section .resume-item .resume-date {
    min-width: 18rem;
  }
}

@media (min-width: 992px) {
  section.resume-section {
    padding-top: 3rem !important;
    padding-bottom: 3rem !important;
  }
}

.bg-primary {
  background-color: #BF0603 !important;
}

.text-primary {
  color:  #BF0603 !important;
}

a {
  color:  #BF0603;
}

a:hover, a:focus, a:active {
  color: #824027;
}
</style>