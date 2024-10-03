<template>
    <div class="about">
     
        <h1>{{msg}}</h1>
        <div class="about-container">
    
            <div class="img-container">
                <img src="./assets/logo.png">
            </div>
            <div class="about-info">
                <p>Freshly brewed in March 2024, Cuppa Connections isn’t just a coffee shop. We’re also passionate about promoting connections between young minds and creative souls, which is fueled by our top-notch specialty coffee. We assure to deliver the finest, quality beans that are roasted to perfection, for customers to have an unforgettable experience. Whether you are a newcomer, or a coffee enthusiast, our welcoming baristas can craft the perfect cup to kickstart your day.</p>
            </div>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'about',
    data() {
      return {
        msg: 'Our Story'
      }
    }
  }
  </script>
  <style scoped>
  .about-container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    padding:3%
  }

.about-info {
    padding: 10% 5%
}
 
  </style>