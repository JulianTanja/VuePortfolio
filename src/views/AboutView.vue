<template>
  <div class="about">
    <div class="imagesection">
      <!--put image here-->
      <img :src="image" class="image"/>

    </div>
    <div class="textsection">
      <p>Hello there! My name is Julian, and I'm a rising senior majoring in Computer Science at Boston University. I was born and raised in Jakarta, Indonesia. I'm passionate about front-end software engineering and 
        mobile/web app development, and I'm also currently learning some back-end development too. 
      </p>
      <p>During my time at BU, some of the classes I've taken are Data Structures and Algorithms, Software Engineering, Database Systems, and Concepts of Programming Languages. </p>
      <p>In my free time, I like to lift weights, read books, spar with friends, or play classical piano.</p>
      <p>Currently, I am seeking full-time positions in the United States, and will require sponsorships as an international student on an F-1 visa.</p>
    </div>
  </div>
</template>

<script>
  import profileimage from "../assets/images/IMG_8053.jpg";

  export default {
    data() {
      return {
        image: profileimage
      }
    }
  }
</script>

<style>

.imagesection{
  margin-right: 400px;
  position: relative;  
  right: 140px;
  top: 10px;

}

.image {
  height: 600px;
  width: 450px;
}

.textsection{
  text-align: justify;
  margin-left: 650px;
  margin-right: 30px;
  word-wrap: break-word;
  position: relative;
  bottom: 450px;
}

.about {
  height: 700px;
}

</style>


