<template>
    <v-app id="inspire" background-color="#B0BEC5">
        <v-app-bar>
            <v-subheader class="title"><h1 class="indigo--text">Portfolio</h1></v-subheader>
            <v-tabs center-active right background-color="transparent" active-class="active-tab">
                <v-tab href="#home">Home</v-tab>
                <v-tab>About</v-tab>
                <v-tab>Portfolio</v-tab>
                <!-- <v-tab>Blog</v-tab> -->
                <v-tab>Contact</v-tab>
            </v-tabs>
          
        </v-app-bar>
        <v-main style="background-color: #F5F5F5">
            <section class="intro-section" id="home">
                <v-row class="align-center px-10" style="height: 500px">
                <v-col lg="4" cols="12"></v-col>
                    <v-col lg="4" cols="12" class="pa-6 font-weight-bold py-16">
                        <h2 class="display-3">Web Development<span class="black--text"></span><h2 class="align-center display-3">Enthusiast</h2></h2> 
                        <v-subheader class="subtitle-1">Hi, I am Fairuz, focusing on gathering professional experiences.</v-subheader>
                        <v-row class="mt-5">
                            <v-chip class="px-4 ma-3" color="info">
                                <v-icon left size="20">mdi-linkedin</v-icon>
                                <!-- <a href="www.linkedin.com/in/fairuztanzimachal"><v-icon></v-icon></a> -->
                                Linkedin
                            </v-chip>
                            <v-chip class="px-4 ma-3" color="dark">
                                <v-icon left size="20">mdi-github</v-icon>
                                Linkedin
                            </v-chip>
                        </v-row>
                    </v-col>
                    <v-col lg="4" cols="12"></v-col>
                    <!-- <v-col lg="6" cols="6">
                        <v-img src="https://preview.colorlib.com/theme/jackco/assets/img/hero/xhero_right.png.pagespeed.ic.U76_mb-Zcf.webp"></v-img>
                    </v-col> -->
                </v-row>
            </section>
            <section class="about-me" id="about">
                <!-- <v-img class="pa-10" height="400" gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                       src="https://designshack.net/wp-content/uploads/Home-office.jpg"> -->
                    <v-row justify="center" class="align-center" style="height: 300px">
                        <v-col lg="6" cols="6">
                            <v-card class="text-center pa-6 rounded-lg" color="#e1e0e0c9" elevation="6">
                                <v-card-subtitle class="indigo--text">ABOUT MYSELF</v-card-subtitle>
                                <h3>
                                    A highly motivated BSc (CSE) final semester student, seeking to get a position in a reputed company where I
can use my skills and knowledge to learn new things. An enthusiastic learner having good communication
skill, currently seeking for an internship or related employment opportunity.
                                </h3>
                                <v-btn large elevation="5" color="indigo" class="white--text mt-10 px-10 py-5">Download
                                    Resume
                                    <v-icon>mdi-download</v-icon>
                                </v-btn>
                            </v-card>
                        </v-col>
                        <!-- <v-col lg="6" cols="6">
                            <v-card class="pa-6 rounded-lg" color="#e1e0e0c9" elevation="6">
                                <div class="py-1" v-for="(item,index) in items" :key="index">
                                    <label>{{ item.title }}</label>
                                    <v-progress-linear
                                            :color="item.color"
                                            height="10"
                                            :value="item.value"
                                    ></v-progress-linear>
                                </div>
                            </v-card>
                        </v-col> -->
                    </v-row>
                <!-- </v-img> -->
            </section>



            <section class="educaion py-6" >
                <v-container>
                    <h4 class="display-2 text-center">Education</h4>
                    <v-row class="py-8" >
                        <v-col cols="12" lg="4">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h3>International University of Business Agriculture and Technology (IUBAT)</h3>
                                        <h4>BSc in Computer Science and Engineering</h4>
                                        <h4>CGPA: 3.48</h4>
                                        <span>2019 – present </span>
                                    </div>
                                    <a href="https://iubat.edu/" class="green--text">at IUBAT <v-icon color="green">mdi-link</v-icon></a>
                                    
                                    
                                </div>
                                
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="4">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h3>Uttara High School and College</h3>
                                        <h4>Higher Secondary School Certificate</h4>
                                        <h4>GPA: 4.08</h4>
                                        <span>2016 – 2018 </span>
                                    </div>
                                    <a href="http://uhscdhaka.edu.bd/" class="green--text">at UHSC<v-icon color="green">mdi-link</v-icon></a>
                                </div>
                                
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="4">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h3>Uttara High School and College</h3>
                                        <h4>Secondary Secondary School Certificate</h4>
                                        <h4>GPA: 5.00</h4>
                                        <span>2015 – 2016 </span>
                                    </div>
                                    <a href="http://uhscdhaka.edu.bd/"  class="green--text">at UHSC<v-icon color="green">mdi-link</v-icon></a>
                                </div>
                                
                            </v-card>
                        </v-col>
                    </v-row>
                </v-container>
            </section>





            <section class="educaion py-6">
                <v-container>
                    <h4 class="display-2 text-center">Skills</h4>
                    <v-row class="py-8">
                        <v-col cols="12" lg="3">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Programming Languages</h2>
                                        <span>C++, Python, HTML, CSS, Bootstrap</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="3">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Web Design</h2>
                                        <span>HTML, CSS, Bootstrap</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="3">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Machine Learning</h2>
                                        <span>Python, SQL</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="3">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>MS Office</h2>
                                        <span>Word, Excel, PowerPoint</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                       
                       
                    </v-row>
                </v-container>
            </section>


            <section class="educaion py-6">
                <v-container>
                    <h4 class="display-2 text-center">Projects</h4>
                    <v-row class="py-8">
                        <v-col cols="12" lg="6">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Online Shopping Management System</h2>
                                        <span>This project was assigned by our course instructor in Database Management System course.
I worked in the frontend part of this project.</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="6">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Car Sales and Inventory Store</h2>
                                        <span>It was assigned in Software Engineering course.
I worked in the frontend part of this project.</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        
                       
                       
                    </v-row>
                </v-container>
            </section>



            <section class="educaion py-6">
                <v-container>
                    <h4 class="display-2 text-center">References</h4>
                    <v-row class="py-8">
                      <v-col cols="12" lg="3"></v-col>
                        <v-col cols="12" lg="3">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Dr. Utpal Kanti Das</h2>
                                        <span>Professor & Chair, IUBAT<br> ukd@iubat.edu</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="3">
                            <v-card class="pa-6 rounded-xl " elevation="5">
                                <div class="d-flex align-center justify-space-between">
                                    <div class="">
                                        <h2>Mostafa Shamin Yeasar</h2>
                                        <span>Software Engineer, BJIT<br>mostafa.yeasar@bjitgroup.com, +8801756568927</span>
                                    </div>
                                </div>
                            </v-card>
                        </v-col>
                        <v-col cols="12" lg="3"></v-col>
                        
                       
                       
                    </v-row>
                </v-container>
            </section>

            


        </v-main>
    </v-app>
</template>

<!-- <script>
    export default {
        name: 'App',
        data: () => ({
            drawer: null,
            items: [
                {title: 'HTML', value: 100, color: 'light-blue'},
                {title: 'CSS', value: 100, color: 'deep-orange'},
                {title: 'Javascript', value: 70, color: 'light-green'},
                {title: 'Vuejs', value: 80, color: 'blue'},
                {title: 'Vuetify', value: 90, color: 'black'},
                {title: 'PHP', value: 100, color: 'red'},
            ],
            experience: [
                {
                    title: 'User Experience Designer',
                    date: 'March 2020 - Present',
                    institute: 'Web Burden',
                    decription: 'Proin laoreet elementum ligula, ac tincidunt lorem accumsan nec. Fusce eget urna ante. Donec massa velit, varius a accumsan ac, tempor iaculis massa. Sed placerat justo sed libero varius vulputate.'
                },
                {
                    title: 'UI Designer',
                    date: 'March 2020 - Present',
                    institute: 'Web Burden',
                    decription: 'Proin laoreet elementum ligula, ac tincidunt lorem accumsan nec. Fusce eget urna ante. Donec massa velit, varius a accumsan ac, tempor iaculis massa. Sed placerat justo sed libero varius vulputate.'
                },
                {
                    title: 'Illustration Artiest',
                    date: 'March 2020 - Present',
                    institute: 'Web Burden',
                    decription: 'Proin laoreet elementum ligula, ac tincidunt lorem accumsan nec. Fusce eget urna ante. Donec massa velit, varius a accumsan ac, tempor iaculis massa. Sed placerat justo sed libero varius vulputate.'
                },
                {
                    title: 'Graphic Designer',
                    date: 'March 2020 - Present',
                    institute: 'Web Burden',
                    decription: 'Proin laoreet elementum ligula, ac tincidunt lorem accumsan nec. Fusce eget urna ante. Donec massa velit, varius a accumsan ac, tempor iaculis massa. Sed placerat justo sed libero varius vulputate.'
                },
            ],
            // sliders:[
            //     'https://cdn.searchenginejournal.com/wp-content/uploads/2020/01/which-web-design-platform-is-right-for-you-5e4d59fb941b9-1520x800.png',
            //     'https://cdn.searchenginejournal.com/wp-content/uploads/2019/12/5-ways-seo-web-design-go-together-5e2945dd5df37.png',
            //     'https://data.whicdn.com/images/350420216/original.jpg?t=1605047796',
            //     'https://1zylgb20pxi7mw2sdr8i4a14-wpengine.netdna-ssl.com/wp-content/uploads/2020/01/projectleft.jpg',
            //     'https://cdn.dribbble.com/users/702789/screenshots/14012516/media/561a8b7e8cbe51c72c18f4ef0dc72676.png?compress=1&resize=400x300',
            //     'https://cdn.dribbble.com/users/2399102/screenshots/15522177/media/346d890482d929610d316938e7d48629.png?compress=1&resize=400x300',
            // ]
        }),
    }
</script> -->
<style>
    .v-tab.active-tab {
        color: #9575CD;
    }
    .v-tab.active-tab::before {
        background-color: #4caf50;
    }
</style>