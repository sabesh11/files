<template>
<div class="q-pa-md">
    <div class="container q-mt-xl">
        <div class="row justify-around" >
            <div class="col-md-6 self-center col-12" >
                
               <span class="text-h4 text-red"> Who’s a front-end developer?</span><br><br>
<p class="text-body1" style="line-height: 2.0;">A front-end developer is one who works on the design and implementation of the interface.
 He/She is responsible for the look and feel of the website. Front-end developers need to have a good command of programming languages
 like<span class="text-red"> HTML, CSS,</span> and <span class="text-red"> JavaScript.</span> The look, navigation, and layouts are all made by front-end developers.</p>
            </div>
            <div class="col-md-4 text-center col-12">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSaTRtxmxrywkA5r0wEiGNwIhMnIyeVtYFhzg&usqp=CAU"/>

                <!-- <timeline></timeline> -->
            </div>
        </div>
    </div>
</div>

</template>

<script>
import timeline from'../components/timeline.vue'
export default{
    name:"frontend",
    components:{
        timeline
    }
}

</script>

<style scoped>


</style>