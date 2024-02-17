<template>
     <q-header elevated class="bg-deep-purple-8 text-white rounded-borders q-pa-sm" height-hint="98">
        <q-toolbar>
            <q-toolbar-title>
                <!-- <q-avatar>
        <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
      </q-avatar>  -->
                <span class="text-white text-h5"><span class="text-red">Edex</span> Tech</span>
            </q-toolbar-title>
            <q-tabs align="right" class="gt-sm">
                <q-tab to="/page1" label="About Edex" />
                <q-tab to="/page3" label="curiculam" />
                <q-tab to="/page2" label="Fees" />
                <q-tab to="#placement" label="Placement" />

                <q-tab to="/page3" label="Contact us" />
            </q-tabs>
        </q-toolbar>

        <!-- <q-tabs align="center">
    <q-route-tab to="/page1" label="Page One" />
    <q-route-tab to="/page2" label="Page Two" />
    <q-route-tab to="/page3" label="Page Three" />
  </q-tabs> -->
    </q-header>

<q-page class="container ">
    <div class="row justify-center cc   q-p-xl desktop-only">

        <div class="col-12 col-md-8  ">
            <h3>Essential Front-End Developer Skills: The Top 5 You Can’t-Miss</h3>
        </div>

    </div>
    <div class="row  ccc mobile-only">

        <div class="col-12  ">
            <h4>Essential Front-End Developer Skills: The Top 10 You Can’t-Miss</h4>
        </div>

    </div>

    <div class="q-pa-md example-row-variable-width imgg">

        <div class="row justify-center">

            <div class="col-12 text-center">
                <q-img src="https://www.guvi.in/blog/wp-content/uploads/2023/03/skills.jpg" width="757" height="368" class="imgsty" />
            </div>

        </div>
    </div>
    <div class="row q-mt-sm justify-center ">
        <div class="col-10 text-center">
            <h3 class="desktop-only">Welcome to <span class="text-red">EDEX</span> <span class="text-deep-purple-8">TECH</span> </h3>
            <h3 class="mobile-only" style="line-height: 1.5;">Welcome to<br><span class="text-red">EDEX</span> <span class="text-deep-purple-8">TECH</span> </h3>
            <p class="text-body1">At edex, it means achieving real business results that allow you to transform, and not just maintain, your operations.
                Our IT services, industries solutions, and outsourcing bring you a level of certainty that no other competitor can match.</p>
        </div>
    </div>

    <frontend />
    <timeline />
    <div class="q-pa-md q-mt-xl">

        <div class="col-10 q-mt-md">
            <p class="text-h4">Our Front-End Developer Course Duration And Fees</p>
            <p class="text-body1">Front-End Developer certifications typically range from a few weeks to several months, with fees varying based on program and institution.</p>
        </div>
        <q-markup-table class="q-pa-md q-mt-lg" bordered :separator="separator">
            <thead>
                <tr>
                    <th class="text-left">
                        <p class="text-h5">Program Name</p>
                    </th>
                    <th class="text-right">
                        <p class="text-h5">Duration</p>
                    </th>
                    <th class="text-right ">
                        <p class="text-h5">Fees</p>
                    </th>

                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="text-left"><a href="" class="text-deep-purple-8 text-subtitle1 text-weight-bold" style="text-decoration: none; ">Professional Certificate Program in Blockchain
                        </a>
                        <p>Cohort Starts: <span class="text-body2 text-weight-medium">14 Feb, 2024</span></p>
                    </td>
                    <td class="text-right text-body2 text-weight-medium">4 months</td>
                    <td class="text-right text-body2 text-weight-medium">₹ 1,10,000</td>

                </tr>
                <tr>
                    <td class="text-left"><a href="" class="text-deep-purple-8 text-subtitle1 text-weight-bold" style="text-decoration: none; ">Post Graduate Program in Full Stack Web Development
                        </a></td>
                    <td class="text-right text-body2 text-weight-medium">6 months</td>
                    <td class="text-right text-body2 text-weight-medium">99,999</td>

                </tr>

            </tbody>
        </q-markup-table>
    </div>
    <br>

    <div class="container q-mt-xl q-pa-md">
        <div class="row justify-around q-mt-md">
            <div class="col-md-6 col-12">
                <p class="text-body1" style="line-height: 2.0;">
                    <span class="text-h4 text-deep-purple-8"><span class="text-red">Why This</span><br> Intense Training Bootcamp</span> <br><br>
                    When you learn separate modules of courses you cannot get a complete picture of software development.
                    As a Full stack development taining program you get to know all the component parts of any projects
                    and you can fully develop and deploy any products such as media apps,messagigng app etc.<br>
                    <p class="text-red text-weight-bold">"unlock Your Potential,Master the code."</p>
                </p>
            </div>
            <div class="col-md-4 text-center col-12">
                <img src="https://www.guvi.in/blog/wp-content/uploads/2023/03/frontend.jpg" width="100%">
            </div>
        </div>
    </div>
    <div class="container q-mt-xl bg-deep-purple-8 q-pa-xl text-white">
        <div class="row justify-around q-mt-md ">
            <div class="col-md-5 self-center">
                <span>
                    <span class="text-h3">Hands-on learning</span><br><br>
                    Don't just watch or read about someone else coding — write
                    your own code live in our online, interactive platform.
                    You'll even get AI-driven recommendations on what you need to review to help keep you on track.</span>
            </div>
            <div class="col-md-5 col-12  self-center q-mt-md">
                <q-img src="https://static-assets.codecademy.com/assets/course-landing-page/le-review-mobile.gif" />
            </div>
        </div>
    </div><br><br><br>
    <div class="container  career-support">
        <div class="row ">
            <div class="col-12 text-center">
                <h3>Career Support</h3>
                <p class="text-body1">Along with upskilling and
                    preparing you to be a solid engineer, we will help you with your job search and interview preparation as well!</p>
            </div>
        </div>
        <div class="row justify-around">
            <div class="col-md-2 q-mt-md">

                <!-- style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"  -->
                <q-card class="my-card text-black" style="width: 15rem;">
                    <q-card-section class="text-center">
                        <q-img src="https://assets-v2.scaler.com/assets/academy/svg/employer-d308ffc80a2a4dcd539cdfc4da50dec20698c52fff259ff2dae4eea5dfb15e94.svg.gz" height="100px" width="100px" class="justify-center" />

                    </q-card-section>

                    <q-card-section class="q-pt-none">
                        <div class="text-body1">Access job opportunities<br> from our 600+ employer partners</div>
                        <!-- <div class="text-subtitle2">by John Doe</div> -->
                    </q-card-section>
                </q-card>
            </div>
            <div class="col-md-2 q-mt-md">

                <!-- style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"  -->
                <q-card class="my-card text-black" style="width: 15rem;">
                    <q-card-section class="text-center">
                        <q-img src="https://assets-v2.scaler.com/assets/academy/svg/community-6fa9a0023c30456b10b76caa66f2de9daff9a4c74cc61bf19892cff4021c2a94.svg.gz" height="100px" width="100px" class="justify-center" />

                    </q-card-section>

                    <q-card-section class="q-pt-none">
                        <div class="text-body1">Exchange job opportunities with our extensive 20K+ Scaler student community</div>
                        <!-- <div class="text-subtitle2">by John Doe</div> -->
                    </q-card-section>
                </q-card>
            </div>
            <div class="col-md-2 q-mt-md">

                <!-- style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"  -->
                <q-card class="my-card text-black" style="width: 15rem;">
                    <q-card-section class="text-center">
                        <q-img src="https://assets-v2.scaler.com/assets/academy/svg/mock-3ef075c86047b3d501bbef3e91e533db4d3215e30107f5e6645ce11dc7a358eb.svg.gz" height="100px" width="100px" class="justify-center" />

                    </q-card-section>

                    <q-card-section class="q-pt-none">
                        <div class="text-body1">Practice mock interviews with people working in the industry</div>
                        <!-- <div class="text-subtitle2">by John Doe</div> -->
                    </q-card-section>
                </q-card>
            </div>
            <div class="col-md-2 q-mt-md">

                <!-- style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"  -->
                <q-card class="my-card text-black" style="width: 15rem;">
                    <q-card-section class="text-center">
                        <q-img src="https://assets-v2.scaler.com/assets/academy/svg/resume-b9775f453cdc3079a7031ec687839bbdab8b6cadf2c8f68ba0dfaf8e63045e2e.svg.gz" height="100px" width="100px" class="justify-center" />

                    </q-card-section>

                    <q-card-section class="q-pt-none">
                        <div class="text-body1">Optimize your resume & LinkedIn profile with our experienced experts</div>

                    </q-card-section>
                </q-card>

            </div>
        </div>
    </div>
    <placement /><br><br><br>

    <div class="q-mt-xl  container form-container">

        <div class="row q-mt-xl bg-deep-purple-8 text-white item-center">
            <div class="col q-pa-xl ">
                <div class="q-pa-md">
                    <p class="text-h4">Don't be shy! Feel free to contact us!</p>
                    <p class="text-body1 text-weight-medium">
                        Fill out this form and we will get back to you</p>
                </div>
            </div>

        </div>
        <div class="row q-mt-xl mobile-only justify-center">
            <div class="col-11 ">
                <q-card class="my-card bg-white text-black">
                    <q-card-section>
                        <div class="text-h6 text-center">Request More Information</div>
                        <q-input color="purple-12" v-model="text" label="Name">

                        </q-input>
                        <q-input color="purple-12" v-model="text" label="Email">

                        </q-input>
                        <q-input color="purple-12" v-model="text" label="Phone no">

                        </q-input><br>
                        <br>
                        <q-input class="bg-white" v-model="text" filled type="textarea" label="Write an optional message" /><br>
                        <div class="q-gutter-sm">
                            <div>
                                <q-checkbox label="By providing your contact details, you agree to our Privacy Policy" />
                            </div>
                        </div>

                    </q-card-section>

                    <q-card-actions class="text-center justify-center bg-deep-purple-8 text-white">
                        <q-btn flat class="text-center">Submit</q-btn>

                    </q-card-actions>
                </q-card>
            </div>
        </div>
    </div>

    <div class="container desktop-only ">
        <div class="row justify-end form-row ">
            <div class="col-5 q-mr-md">
                <q-card class="my-card bg-white text-black">
                    <q-card-section>
                        <div class="text-h6 text-center">Request More Information</div>
                        <q-input color="purple-12" v-model="text" label="Name">

                        </q-input>
                        <q-input color="purple-12" v-model="text" label="Email">

                        </q-input>
                        <q-input color="purple-12" v-model="text" label="Phone no">

                        </q-input><br>
                        <br>
                        <q-input class="bg-white" v-model="text" filled type="textarea" label="Write an optional message" /><br>
                        <div class="q-gutter-sm">
                            <div>
                                <q-checkbox v-model="right" label="By providing your contact details, you agree to our Privacy Policy" />
                            </div>
                        </div>

                    </q-card-section>

                    <q-card-actions class="text-center justify-center bg-deep-purple-8 text-white">
                        <q-btn flat class="text-center">Submit</q-btn>

                    </q-card-actions>
                </q-card>
            </div>
        </div>
    </div><br>

    <location></location>
</q-page>
</template>

<script>
import location from '../components/EssentialLink.vue'
import frontend from '../components/frontend.vue'
import timeline from '../components/timeline.vue'
import placement from '../components/Placement.vue'
import {
    ref
} from 'vue'

export default {
    setup() {
        return {
            separator: ref('vertical'),
            separatorOptions: [

                {
                    label: 'Cell',
                    value: 'cell'
                },

            ]
        }
    },
    name: 'IndexPage',
    components: {
        location,
        frontend,
        timeline,
        placement
    }
}
</script>

<style>
.cc {
    background-image: url('https://blog.guvi.in/wp-content/uploads/2022/04/Blog-heading.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 100px;
    /* background-color: red; */

    /* transition: background .3s,border-radius .3s,opacity .3s; */
}

.ccc {
    background-image: url('https://blog.guvi.in/wp-content/uploads/2022/04/Blog-heading.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 50px;
}

.imgg {
    position: relative;
    bottom: 90px;
}

.imgsty {
    width: 80%;
    transition-duration: 2s;
    border-radius: 5px 5px 5px 5px;
    box-shadow: 0 0 20px 0 rgba(0, 0, 0, .2);
}

.form-row {
    position: relative;
    bottom: 300px;
}

@media (min-width:1025px) {

    .form-container {
        margin-top: 10rem !important;
    }
}
</style>
