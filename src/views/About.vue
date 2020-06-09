<template>
 
 <div class="container main animated fadeInUp">

   <div class="row">
      <div class="col s12 m4">    
          <div class="row">
    <div class="col s12 m12">
      <div class="card">
        <div class="card-image">
          <img src="../assets/images/pp.jpg">
          
        </div>
       
       
      </div>
    </div>
  </div>
        

</div>

      <div class="col s12 m8 ">
      Software Engineer passionate about developing innovative
      products geared toward simplifying & Improving life.

      I am currently building @WebberTM 🔥
        <br/>


      </div>
    
    </div>
<br/>

     <h5>Tools & Technologies:</h5>   <br/>
     <div> <span class="chip grey" v-for="(tool, index) in tools" :key="index"> {{tool}}</span>
     
     
     </div>  

     <br/>

 </div>
</template>


<script>
export default {
  name: "About",

  data(){
    return{
      tools : ["Node Js", "Express", "Vue Js", "HTML5 & CSS3", "Git & Github", "Sketch", "IBM Watson","AJAX", "Java", "Learning React & GraphQL"]
    }
  }
}
</script>



<style>
.main{
  margin-top: 130px
}

body{
  color:white
}

.chip{
  color:white
}
</style>
