<template>
    <div class="gallery">
        <h1>{{ title }}</h1>
        <div class="main-container">
    <div class="container py-5 ">   
        <div class="row row-cols-1 row-cols-md-3 gy-4 py-5">

                <div class="col">
                    <div class="card">
                        <img src="./assets/dish1.png" class="card-img-top" alt="...">
                        <div class="card-body">
                          <h5 class="card-title">Matcha White Chocolate Cookies</h5>
                          <p class="card-text">Indulge in the perfect balance of earthy matcha and creamy white chocolate in every bite of our matcha cookies.</p>
                        </div>
                      </div>
                </div>
                <div class="col">
                  <div class="card">
                      <img src="./assets/dish2.png" class="card-img-top" alt="...">
                      <div class="card-body">
                            <h5 class="card-title">Crookies</h5>
                            <p class="card-text">Savor the delightful fusion of two beloved classics of croissants and chocolate chip cookies.</p>
                           
                      </div>
                  </div>
              </div>
              <div class="col">
                <div class="card">
                    <img src="./assets/dish3.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Biscoff Cheesecake</h5>
                        <p class="card-text">Indulge in our moist cheesecake. a creamy, rich, decadent cheesecake topped with biscoff biscuits.</p>
                       
                    </div>
                </div>
            </div>
            <div class="col">
              <div class="card">
                  <img src="./assets/dish4.png" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Peka Mayap</h5>
                    <p class="card-text">Shaken espresso with white chocolate and caramel sauce. One of our best-selling drinks.</p>
                  </div>
              </div>
          </div>
          <div class="col">
            <div class="card">
                <img src="./assets/dish5.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Matcha Latte</h5>
                  <p class="card-text">Grinded green tea mixed with creamy milk and vanilla.</p>
                </div>
            </div>
          </div>

            <div class="col">
              <div class="card">
                  <img src="./assets/dish6.png" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Kuti Berry</h5>
                    <p class="card-text">Refreshing drink with strawberry bits, soda, and yakult.</p>
                  </div>
              </div>
          </div>
        </div>
    </div> 
    <div class="empty-div">
    </div>
    </div>  

    </div>
</template>

<script>
export default {
    name: 'gallery',
    data(){
        return{
            title:'Our Gallery'
        }
    }
}
</script>

<style scoped>


</style>