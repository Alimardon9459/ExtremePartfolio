<template>
  <div class="container">

      <div class="text-white content row justify-center items-center">
        <div class="text-center">
          <div>
            <span >TESTIMONIALS</span>
          </div>
          <div class="q-mt-lg">
            <span class="text-h4 q-mt-lg">Our Riders Said About Us</span>
          </div>
        </div>
      </div>
      <div class="carousel">
        <q-carousel
          class="carousel"
          animated
          v-model="slide"
          navigation
          infinite
          :autoplay="autoplay"
          transition-prev="slide-right"
          transition-next="slide-left"
          @mouseenter="autoplay = false"
          @mouseleave="autoplay = true"
        >
          <q-carousel-slide :name="1">
              <div class="text-white carousel-bit text-center row wrap justify-center">
                <div class="col-10">
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                </div>
                <div style="font-size:20px; line-height:1.8; width:50%">
                  <span >
                    “It was an awesome experience! Exhausting though, but super fun and definitely worth it. Very beautiful piece of nature! I highly recommend it :)”
                  </span>
                </div>
                <div class="row col-10 justify-center">
                  <div>
                    <q-img width="75px" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group-13.png"/>
                  </div>
                  <div class="q-ml-lg" >
                    <div class="text-h6 q-mt-md">
                      Andrew Gosha
                    </div>
                    <div class="text-start">
                      Pro Rider
                    </div>
                  </div>
                </div>
              </div>
            </q-carousel-slide>
             <q-carousel-slide :name="2">
              <div class="text-white carousel-bit text-center row wrap justify-center">
                <div class="col-10">
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                </div>
                <div style="font-size:20px; line-height:1.8; width:50%">
                  <span >
                    “It was an awesome experience! Exhausting though, but super fun and definitely worth it. Very beautiful piece of nature! I highly recommend it :)”
                  </span>
                </div>
                <div class="row col-10 justify-center">
                  <div>
                    <q-img width="75px" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group-13.png"/>
                  </div>
                  <div class="q-ml-lg" >
                    <div class="text-h6 q-mt-md">
                      Andrew Gosha
                    </div>
                    <div class="text-start">
                      Pro Rider
                    </div>
                  </div>
                </div>
              </div>
            </q-carousel-slide>
             <q-carousel-slide :name="3">
              <div class="text-white carousel-bit text-center row wrap justify-center">
                <div class="col-10">
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                  <q-icon color="yellow" size="20px" name="star"/>
                </div>
                <div style="font-size:20px; line-height:1.8; width:50%">
                  <span >
                    “It was an awesome experience! Exhausting though, but super fun and definitely worth it. Very beautiful piece of nature! I highly recommend it :)”
                  </span>
                </div>
                <div class="row col-10 justify-center">
                  <div>
                    <q-img width="75px" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group-13.png"/>
                  </div>
                  <div class="q-ml-lg" >
                    <div class="text-h6 q-mt-md">
                      Andrew Gosha
                    </div>
                    <div class="text-start">
                      Pro Rider
                    </div>
                  </div>
                </div>
              </div>
            </q-carousel-slide>

        </q-carousel>
      </div>



  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      slide: ref(1),
      autoplay: ref(true)
    }
  }
}
</script>
<style scoped>
  .container{
    width: 100%;
    height: 100vh;
    background-image: url("http://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group-38.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .carousel{
    width: 100%;
    height: 60vh;
  }
  .carousel-bit {
    width: 100%;
    height: 50vh;
  }
  div{
    background: none;
  }
  .content{
    width: 100%;
    height: 40vh;
  }
</style>
