<template>
  <div class="home">
    <!-- <div class="hero">
      <img src="./assets/hero-img.jpg" width="40%" height="40%">
      <div class="centered">
        <h2>The Finest Coffee in town</h2>
        <p>Discover the art of coffee, perfected in every pour, where every cup tells a story of flavor and warmth.</p>

      </div>
    </div> -->
    <h1>{{msg}}</h1>
   <div class="content">
    
    <div id="p-content-container"></div>
    <div class="info">
      <p id="content-info">Originated from the lands of Colombia, our Arabica beans flourished with the perfect combination of altitude, soil, and climate. Upon brewing, an enticing aroma will greet you with that reminiscent sweet caramel and cocoa. The flavors range from a natural sweetness to a subtle nuttiness, with fruity undertones, complimented by a refreshing citrusy finish.</p>
    </div>
    <div class="content-pic">
    <img src="./assets/1.jpg" width="60%" >
   </div>
   </div>
   <h1>Why Choose Us?</h1>
   <div class="choose">
    <div class="choose-container">
      <div class="choose-info">
        <p class="convenience">Convenience</p>
        <p id="c-text">Accessibility is one of the reasons why customers come back, this includes the proximity of public transportation, and parking availability. We are located in an area with high foot traffic as we are near schools and offices, which makes it easier and efficient for people to incorporate to visit the coffee shop in their daily routines.</p>
      </div>
    </div>
    <div class="ambiance-info">
        <p class="ambiance">Ambiance</p>
        <p id="a-text">A welcoming atmosphere makes customers feel comfortable and relaxed where people can gather to connect with their friends, families and colleagues. It can also impact productivity, and we ensure that our shop is well-lit and with a moderate level of background noise to enhance concentration. Making it an ideal place for remote work and studying.</p>
      </div>
      <div class="quality-info">
        <p class="quality">Quality</p>
        <p id="q-text">For us, Coffee isn’t just a drink – it is an experience. We want our customers to have their best coffee experience, that is why our coffee has top-notch quality, leaving you with a nutty, fruity, and citrusy flavor, in line with this, it has a sweet caramel, cocoa aroma. We can assure that customers will be satisfied as we serve coffee that is consistent and reliable.</p>
      </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      msg: 'Our Coffee'
    }
  }
}
</script>
<style scoped>
.choose-info, .ambiance-info, .quality-info {
  padding: 20px;
  justify-content: space-around;
}
h1 {
  padding: 2%;
}

.content, .choose {
  display: flex;
  flex-direction: row;
  justify-content: center;
  padding:3%
}
.content {
  background-color:#e2d9c9;
}
#content-info {
  text-align: center;
  justify-content: center;
  padding: 15%
}
</style>